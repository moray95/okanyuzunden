# okanyuzunden.ooo website

Best website ever, created with [Hugo](https://gohugo.io)

## Run the website

```shell
brew install hugo
hugo server --minify &
open localhost:1313
```

Any changes will be automatically reflected without restarting the server. Any open browser will refresh automatically.

## Add a new page

```shell
hugo new posts/my-new-post.{html,md}
```

Open the newly created file under `content/posts`. Make sure `draft` is set to `false` so your content will be visible.