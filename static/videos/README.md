Place anonymized MP4 files here using these default names:
- retargeting_comparison.mp4
- dynamic_motions.mp4
- hardware.mp4

Before uploading, remove identifying visual content and strip metadata, e.g.:
ffmpeg -i in.mp4 -map_metadata -1 -c copy out.mp4
