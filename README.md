# plced.io

Static placeholder site for plced.io, served by GitHub Pages from the repository root.
It is a single `index.html` with inline CSS and JavaScript that counts down to the next Wednesday in the visitor's local time and celebrates with a frog on Wednesday.
There is no build step.

## DNS records

Add these records at the domain registrar so GitHub Pages serves `plced.io`:

| Host  | Type  | Value                  |
| ----- | ----- | ---------------------- |
| `@`   | A     | `185.199.108.153`      |
| `@`   | A     | `185.199.109.153`      |
| `@`   | A     | `185.199.110.153`      |
| `@`   | A     | `185.199.111.153`      |
| `www` | CNAME | `rickydtran.github.io` |

Optional IPv6 records for the apex:

| Host | Type | Value                 |
| ---- | ---- | --------------------- |
| `@`  | AAAA | `2606:50c0:8000::153` |
| `@`  | AAAA | `2606:50c0:8001::153` |
| `@`  | AAAA | `2606:50c0:8002::153` |
| `@`  | AAAA | `2606:50c0:8003::153` |

The `CNAME` file in this repository sets the custom domain for Pages.
