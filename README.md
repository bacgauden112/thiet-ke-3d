# thiet-ke-3d

Các bản thiết kế 3D (Three.js), mỗi bản là một trang tĩnh, deploy lên Cloudflare Workers dạng static assets.

| Trang | Đường dẫn |
|---|---|
| Góc sân cây mít: khu nướng & uống trà | `/goc-chill/` |

Link: https://thiet-ke.anhdq1102.workers.dev/goc-chill/

## Deploy

```bash
npx wrangler deploy
```

Hoặc kết nối repo này với Cloudflare (Workers & Pages → Create → Import a repository) để mỗi lần push lên `main` thì tự deploy.

## Thêm bản thiết kế mới

Tạo `public/<ten-trang>/index.html`, rồi push lên. Trang sẽ có ở `/<ten-trang>/`.
