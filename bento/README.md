# Bento

![Notebook](assets/notebook.png)
![Snippets](assets/snippets.png)

## Commands

```bash
yt-dlp --format "bestvideo*" "https://youtu.be/f3UfVX4_PD4?si=3eBnQBA0ciqy6MW6"
```

```bash
ffmpeg -ss 00:08:23 -i "Tanya Rai - Introducing Bento： Jupyter Notebooks @ Facebook ｜ JupyterCon 2020 [f3UfVX4_PD4].mp4" -vframes 1 notebook.png
```

```bash
ffmpeg -ss 00:08:31 -i "Tanya Rai - Introducing Bento： Jupyter Notebooks @ Facebook ｜ JupyterCon 2020 [f3UfVX4_PD4].mp4" -vframes 1 snippets.png
```

## References

- https://engineering.fb.com/2024/09/17/data-infrastructure/inside-bento-jupyter-notebooks-at-meta/
- https://developers.facebook.com/blog/post/2021/09/20/eli5-bento-interactive-notebook-empowers-development-collaboration-best-practices/
- https://www.youtube.com/watch?v=f3UfVX4_PD4
