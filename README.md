# video To Carousel Steven

Turn videos, product images, transcripts and ideas into sharp, realistic TikTok carousel images. Default style: independent 3:4 slides, full-bleed photography, prominent product, concise English hooks, bold white text and yellow emphasis.

## Preview

![Approved cover](assets/approved-tiktok/cover.png)

## Install

Copy `the repository folder` into your AI tool's skills directory. For Codex use `~/.codex/the repository folder`; for tools using the Claude skill directory use `~/.claude/the repository folder`. Directory conventions depend on the host application.

Repository: https://github.com/stevechen721513-ui/photo-to-carousel-steven\n\n## Use

`Use $photo-to-carousel-steven to turn this video into eight TikTok carousel images.`

Chinese: `用 $photo-to-carousel-steven，把这个视频做成 8 张 TikTok 轮播图。`

For other AI tools, load SKILL.md, the standard reference and relevant sample images. Each slide must be a separate complete image, never sliced from a collage.

## Requirements

- An image generation/editing tool for the rendered photo-realistic workflow.
- ffmpeg for video metadata and frame extraction.
- yt-dlp only when downloading an online video is needed.
- An available transcription tool or supplied transcript when spoken content matters.

No mandatory Gemini API, Claude plugin, platform-specific script path or personal API key. The host AI's image tool may have its own access or billing requirements.

## Accuracy and scope

Generated detail can differ from the product. Check outputs against original product photos. Do not invent specifications or claim generated images are real product tests. This skill produces image assets; publishing or posting externally requires a separate user request.

## Background

The workflow was developed from video-to-carousel experimentation and an approved RC-truck visual set. Initial inspiration: [Dreydrey9000/claude-skills carousel-maker](https://github.com/Dreydrey9000/claude-skills/tree/main/content-creation/carousel-maker). This distribution contains rewritten instructions and generated style examples; it does not distribute the upstream personal reference photographs, Claude plugin scripts or shared rule files.
