# One Click Auto Tab Group Notices

Remote notice payloads for the One Click Auto Tab Group Chrome extension.

## File format

The extension reads `notices.json` with this shape:

```json
{
  "notices": [
    {
      "id": "notice-unique-id",
      "updatedAt": 1769472000000,
      "link": "https://example.com/details",
      "i18n": {
        "en": {
          "title": "Notice title",
          "body": "Notice text",
          "linkText": "View details"
        },
        "zh_CN": {
          "title": "公告标题",
          "body": "公告内容",
          "linkText": "查看详情"
        }
      }
    }
  ]
}
```

## Publishing via GitHub Pages

1. Enable Pages in repository settings (Deploy from branch: `main` / root).
2. Push changes to `main`.
3. Use the public URL:
   - `https://<username>.github.io/oneclickautotabgroup-notices/notices.json`
