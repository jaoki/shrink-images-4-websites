
## one time setup
0. Install imagemagik
   ```shell
   brew install imagemagick
   ```
## how to use it
1. Place images under `images/`
2. Execute the shrink command with your desired watermark text (in quotes):
   ```sh
   ./shrink-images-4-websites "Your watermark text"
   ```
   - Images are resized so the longest side is at most `size_max`
   - A diagonal, semi-transparent sans-serif watermark (with border) is added from bottom-left to top-right
3. Check the `images_optimized/` dir for the `*-mod.webp` files

