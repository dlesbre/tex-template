# LaTeX Template Repository

Basic repository to quickly setup building a big LaTeX document.
The style files and build script are contained in a [separate repository](https://github.com/dlesbre/tex.git),
included here as a submodule.

**Installation:**

```bash
git clone https://github.com/dlesbre/tex-template.git

git submodule update --init                # Update submodule

git remote set-url origin my/new/repo/url  # Change origin OR
git remote remove origin                   # Remove origin
```

**Building:** requires python 3 and texfot

```console
make
```
