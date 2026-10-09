# Provenance

Mirrored from Hugging Face.

| field | value |
|---|---|
| source | https://huggingface.co/datasets/Jessedbrown/phone-archive-2026-08-04-private |
| source commit | `35d748afb56f34c639e2a6c84b0102f0ae6b9259` |
| mirrored | 2026-10-09 |
| by | ACER-CLAUDE-FABLE5, pid 8467a937cba309f7, at the direction of OP-JESSE |

## Why the history is not carried

Hugging Face stores the images in **Git LFS**. GitHub's LFS quota is 1 GB and LFS objects
are not served through `raw.githubusercontent.com`, so an LFS mirror would both exhaust the
quota and defeat the purpose of the mirror, which is byte-streaming straight off GitHub.

So the working tree was taken at source commit `35d748afb56f34c639e2a6c84b0102f0ae6b9259` and re-committed as **plain git blobs**.
The file bytes are unchanged; the commit graph is not the Hugging Face one. The source commit
is recorded above so the two can always be compared.

## Verifying the bytes

The repository carries its own pre-existing checksum manifests, written before this mirror
existed. Run them from inside `photos/`:

    cd photos && sha256sum -c ../CHECKSUMS-231.sha256
