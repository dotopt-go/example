# example

## bazel编译

1. generate

    ```bash
    bazel run //:gazelle
    ```

2. 编译

    ```bash
    bazel query //...
    bazel build //:example
    bazel run //:example
    ```

## go 编译

```bash
go build
```
