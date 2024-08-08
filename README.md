English | [中文](https://noviachen.github.io/posts/fcde2f81.html)

# Image Builder

Use Github Action for a easier way to compile firmwares with Image Builder.

## Usage

- Click the [Use this template](https://github.com/noviachen/Image-Builder/generate) button to create a new repository.
- By default, ImmortalWrt 23.05.3 (r27917-81a1f98d5b) is used. To change it, modify the `DOWNLOAD_URL` in `.github/workflows/image-builder.yml`. May also be applicable for compiling the official OpenWrt version (untested).
- Modify the `PROFILE` in image-builder.yml according to your device.
- Modify `uci-custom` (first boot script) and `packages.list` (to add or remove packages) as needed.
- Upload other ipk files to the `packages` folder (if any).
- Select `ImmortalWrt Image Builder` on the Actions page.
- Click the `Run workflow` button.
- When the build is completed, click the file links under `Artifacts` to download the firmwares.

## Thanks

- [GitHub Actions](https://github.com/features/actions)
- [OpenWrt](https://github.com/openwrt/openwrt)
- [Project ImmortalWrt](https://github.com/immortalwrt/immortalwrt)

## Reference

[ImmortalWrt Image Builder 使用说明](https://github.com/1715173329/blog/issues/8)

## License

[MIT](https://github.com/noviachen/Image-Builder/blob/main/LICENSE)
