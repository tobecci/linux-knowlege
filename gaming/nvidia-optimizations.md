[up](./README.md)

# How to improve game performance for lutris on nvidia PC

- go to preferences > global options > environment variables
    - set the `Vulkan ICD loader` to `Nvidia Proprietary`
    - and set the following environment variables
    ```bash
    __GL_SHADER_DISK_CACHE_PATH=/path/to/a/custom/location
    __GL_SHADER_DISK_CACHE_SKIP_CLEANUP=1
    ```