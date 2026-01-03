
## one time setup
0. Install ImageMagick
   ```shell
   brew install imagemagick
   ```
## how to use it
1. Place images under `images/`
2. Execute the shrink command with one of the following options:
   
   **Option 1: With watermark**
   ```sh
   ./shrink-images-4-websites --watermark "Your watermark text"
   ```
   
   **Option 2: Without watermark**
   ```sh
   ./shrink-images-4-websites --no-watermark
   ```
   
   - Images are resized so the longest side is at most `size_max` (600px)
   - When using `--watermark`, a diagonal, semi-transparent sans-serif watermark (with border) is added from bottom-left to top-right
   - Either `--no-watermark` or `--watermark` with text must be provided
3. Check the `images_optimized/` dir for the `*-mod.webp` files

