# hexo-asset-image-fix

Fork [hexo-asset-image](https://github.com/CodeFalling/hexo-asset-image),fixed image path not using root path in hexo configuration.

Give asset image in hexo a absolutely path automatically

# Usege

```shell
npm install hexo-asset-image-fix --save
```

# Example

```shell
MacGesture2-Publish
├── apppicker.jpg
├── logo.jpg
└── rules.jpg
MacGesture2-Publish.md
```

Make sure `post_asset_folder: true` in your `_config.yml`.

Just use `![logo](logo.jpg)` to insert `logo.jpg`.
