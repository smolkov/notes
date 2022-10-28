# gcc

* [gcc memory sanitizer](#gcc-memory-sanitizer)

## gcc memory sanitizer

### Setup in makefile

C_FLAGS_GENERAL   += -fsanitize=address -fsanitize=undefined -fsanitize-recover=all
LINKER_FLAGS_IDA += -fsanitize=address -fsanitize=undefined -static-libasan -static-libubsan

### run

```sh
ASAN_OPTIONS=halt_on_error=0:fast_unwind_on_malloc=0:detect_leaks=0 UBSAN_OPTIONS=print_stacktrace=1 ./rs
```