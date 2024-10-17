# Running [Prodigy AI](https://prodigy.ai/) on [Upsun](https://upsun.com)

Build AI systems that do exactly what you want: A modern data development experience from the makers of SpaCy

## Setup / Deployment
1. Install the Upsun CLI
2. Clone the project.

```bash
upsun project:create
```

```bash
upsun var:create --level=project env:PIP_EXTRA_INDEX_URL --value=https://REPLACE-WITH-YOUR-KEY@download.prodi.gy
```

```bash
upsun push
```

You should look at .upsun/config.yaml for the build and start hooks.