# AGL Handbook

## Editing Content

### Markdown

### Section Metadata

Each section has a yaml header, such as the below. 

```markdown
---
title: GOV.UK on Agile
order: 400
style: black
youtube_video_id: 0XpAtr24uUQ
---
```

The metadata you can provide are:
 * __title (required):__ The section title that will appear as the section header. 
 * __order (required):__ Sort order, as compared to other sections, with lower numbers shown first. To insert a section between About Agile (100) and History (200), set the order of the new section to 150.
 * __style (optional):__ Section styling, which defaults to white background. Options: white, black, grey.
 * __youtube_video_id (optional):__ If present, this will embed a video after section content. The id is the alphanumeric code such as "0XpAtr24uUQ". This can be found in the video's URL, e.g. the bit after `v=` in `https://www.youtube.com/watch?v=0XpAtr24uUQ`.

## Maintaining the Template

To make changes to the overall page template to stay in coordination with the overall AGL site, edit `layouts/agl.html`. This would include major style changes or updated top-level navigation, footer info, etc.

## Running Locally
