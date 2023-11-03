# consulminds.github.io

## How to run

### Using docker

In project root directory, run
`docker run --rm -it -v $(pwd):/src -p 1313:1313 klakegg/hugo server --noHTTPCache`

## Custom Domain configuration

Apart from [GitHub doc](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site#configuring-a-subdomain), this [StackOverflow answer](https://stackoverflow.com/a/9123911) helped a lot to setup custom domains.

`consulminds.com` redirects to `www.consulminds.com`
