# Eyüp Can Akman

I'm the technical lead at [Evrim Ağacı](https://evrimagaci.org), a Turkish popular science platform with millions of readers a month.
I also co-founded [Kreosus](https://kreosus.com), where supporters fund independent creators.
Most of what I build is payment systems and marketplaces, plus the servers they run on.
There is more about that on [eyupcanakman.com](https://eyupcanakman.com).

Nearly all of my GitHub activity is in private repositories, mostly for that work.
In early 2026 I started sending fixes to open source projects. I began with tools from my own stack and went on from there.
This page is the public part.

## Projects I keep coming back to

Each project name links to the full list of what landed there.
Most of the merged pull requests are under 100 lines, and most come with a test.

| Project | Examples |
|---|---|
| [symfony/symfony](https://github.com/symfony/symfony/pulls?q=is%3Apr+author%3Aeyupcanakman+is%3Amerged) | Yaml parser fixes for [block scalars](https://github.com/symfony/symfony/pull/68024), [aliases](https://github.com/symfony/symfony/pull/65425) and [line folding](https://github.com/symfony/symfony/pull/64672), plus [Form](https://github.com/symfony/symfony/pull/64536), [Serializer](https://github.com/symfony/symfony/pull/64225) and [HttpKernel](https://github.com/symfony/symfony/pull/63555) |
| [php/php-src](https://github.com/php/php-src/commits?author=eyupcanakman) | [Stack overflow in `mb_check_encoding()`](https://github.com/php/php-src/commit/49b9884355), [wrong `mb_strrpos()` result outside UTF-8](https://github.com/php/php-src/commit/0d6ab5321d), [ZipArchive stream truncation](https://github.com/php/php-src/commit/5a326b9a43) |
| [composer/composer](https://github.com/composer/composer/pulls?q=is%3Apr+author%3Aeyupcanakman+is%3Amerged) | [Local change check when switching from source to dist](https://github.com/composer/composer/pull/12912), [host matching in `Url::getOrigin`](https://github.com/composer/composer/pull/12988) |
| [ml-explore/mlx](https://github.com/ml-explore/mlx/pulls?q=is%3Apr+author%3Aeyupcanakman+is%3Amerged) | [`stft` and `istft`](https://github.com/ml-explore/mlx/pull/3639), [integer overflow in convolution shapes](https://github.com/ml-explore/mlx/pull/3938), [`conv_transpose` buffer limits on Metal](https://github.com/ml-explore/mlx/pull/3845) |
| [uutils/coreutils](https://github.com/uutils/coreutils/pulls?q=is%3Apr+author%3Aeyupcanakman+is%3Amerged) | [`install -D` race losing files](https://github.com/uutils/coreutils/pull/12429), [`printf` and `seq` padding and panics](https://github.com/uutils/coreutils/pull/13460), [locale decimal separator in `du`](https://github.com/uutils/coreutils/pull/12357) |
| [google/highway](https://github.com/google/highway/pulls?q=is%3Apr+author%3Aeyupcanakman+is%3Amerged) | [`ShiftRightAndDemoteTo` ops](https://github.com/google/highway/pull/3056) with [RVV](https://github.com/google/highway/pull/3140) and [LSX](https://github.com/google/highway/pull/3160) overrides |
| [hickory-dns/hickory-dns](https://github.com/hickory-dns/hickory-dns/pulls?q=is%3Apr+author%3Aeyupcanakman+is%3Amerged) | [CNAME chain ordering in recursor answers](https://github.com/hickory-dns/hickory-dns/pull/3836), [NXDOMAIN short-circuit](https://github.com/hickory-dns/hickory-dns/pull/3784) |
| [square/kotlinpoet](https://github.com/square/kotlinpoet/pulls?q=is%3Apr+author%3Aeyupcanakman+is%3Amerged) | [`CodeBlockHolder`](https://github.com/square/kotlinpoet/pull/2331), [recursively bound generics](https://github.com/square/kotlinpoet/pull/2320), [indent leaking out of expression bodies](https://github.com/square/kotlinpoet/pull/2365) |
| [apple/coremltools](https://github.com/apple/coremltools/pulls?q=is%3Apr+author%3Aeyupcanakman+is%3Amerged) | [`pow` with a constant base of 2](https://github.com/apple/coremltools/pull/2742), [einsum ellipsis lowering](https://github.com/apple/coremltools/pull/2706), [`torch.tensor_split`](https://github.com/apple/coremltools/pull/2715) |
| [emdash-cms/emdash](https://github.com/emdash-cms/emdash/pulls?q=is%3Apr+author%3Aeyupcanakman+is%3Amerged) | [Dangerous URL schemes in menu links](https://github.com/emdash-cms/emdash/pull/94), [R2 `publicUrl` ignored for rendered media](https://github.com/emdash-cms/emdash/pull/675) |
| [Sequel-Ace/Sequel-Ace](https://github.com/Sequel-Ace/Sequel-Ace/pulls?q=is%3Apr+author%3Aeyupcanakman+is%3Amerged) | [Connection lock on ProxySQL](https://github.com/Sequel-Ace/Sequel-Ace/pull/2450), [literal `$N` in query favorites](https://github.com/Sequel-Ace/Sequel-Ace/pull/2434) |

php-src merges by hand, so my pull requests there show as closed. That link goes to the commits.

Smaller amounts went to [typesense-php](https://github.com/typesense/typesense-php/pulls?q=is%3Apr+author%3Aeyupcanakman+is%3Amerged) and [gorse](https://github.com/gorse-io/gorse/pulls?q=is%3Apr+author%3Aeyupcanakman+is%3Amerged), which I run in production.
The rest is spread over [nomad](https://github.com/hashicorp/nomad/pulls?q=is%3Apr+author%3Aeyupcanakman+is%3Amerged), [gitea](https://github.com/go-gitea/gitea/pulls?q=is%3Apr+author%3Aeyupcanakman+is%3Amerged), [restic](https://github.com/restic/restic/pulls?q=is%3Apr+author%3Aeyupcanakman+is%3Amerged), [hurl](https://github.com/Orange-OpenSource/hurl/pulls?q=is%3Apr+author%3Aeyupcanakman+is%3Amerged), [numba](https://github.com/numba/numba/pulls?q=is%3Apr+author%3Aeyupcanakman+is%3Amerged), [detekt](https://github.com/detekt/detekt/pulls?q=is%3Apr+author%3Aeyupcanakman+is%3Amerged), [zstd](https://github.com/meta/zstd/pulls?q=is%3Apr+author%3Aeyupcanakman+is%3Amerged) and a long tail of others.

## My own projects

- [gsc-mcp-rs](https://github.com/eyupcanakman/gsc-mcp-rs) is a Google Search Console MCP server in Rust, published on [crates.io](https://crates.io/crates/gsc-mcp-rs).
- [simple-html-dom](https://github.com/eyupcanakman/simple_html_dom) is my maintained fork of voku's HTML DOM parser for PHP, published on [Packagist](https://packagist.org/packages/eyupcanakman/simple-html-dom).
- [htmlawed](https://github.com/eyupcanakman/htmlawed) is htmLawed packaged for PHP 8.4 and later, also on [Packagist](https://packagist.org/packages/eyupcanakman/htmlawed).
