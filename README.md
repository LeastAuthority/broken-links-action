# broken-links
GitHub action to detect broken links in HTML content.

It has been created to detect local broken links only.

## Usage

```yaml
    - name: Detect broken links
      id: tmpfs
      uses: LeastAuthority/broken-links-action@v1
      with:
        path: path/to/html
        root: readme.html
```
