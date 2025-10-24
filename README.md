# 🎬 Auto M3U Combiner

This repository automatically collects and combines multiple `.m3u` playlist URLs into a single master playlist.

## 📦 How It Works
- Add your `.m3u` source links inside `sources.txt`
- Every 6 hours, GitHub Actions downloads and merges all playlists into `master.m3u`
- The master file updates automatically!

## 🔗 Example
You can access your latest master playlist here:
```
https://raw.githubusercontent.com/<your-username>/<your-repo-name>/main/master.m3u
```

Just replace `<your-username>` and `<your-repo-name>` with your own.

Enjoy 🎥
