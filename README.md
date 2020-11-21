Repro steps:

1. Clone this repo
2. yarn install
3. yarn run parcel serve index.html -p 4567 --no-cache

If things were working properly, you'd see `1`, `2`, and `3` on separate lines.
As of now, I see a couple errors like `(index):60 Uncaught Error: Cannot find module '2mVuO` followed by `3`.
