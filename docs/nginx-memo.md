## About Brotli
- GitHub: [ngx_brotli](https://github.com/google/ngx_brotli)

## About Zstd
- GitHub: [zstd-nginx-module](https://github.com/tokers/zstd-nginx-module)

## Performance Tuning

### Minimize Docker Image Size

#### Proposal
- Inspect Docker images.
- Reduce build time.

#### Use `rm -rf /var/lib/apt/lists/*`
- This command helps reduce the size of the Docker image by removing unnecessary APT lists after package installation.
- **Before**: 534MB
- **After**: 492MB
