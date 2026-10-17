# Rooted field journal

Our own photographs will gradually document visited inspiration, research and actual activities. Original concept artwork and illustrated explainers remain separately labeled.

## Easiest update workflow

Share selected photos in the ongoing Rooted chat and say which should be published. Include the date, a short title, what is happening, what inspired you, what you learned and the next question. Location is optional: include only the level of detail you want public. Identify the related stream (learning, growing, land, technology, community or progress). Use photos you have permission to publish, especially when learners or school activities are pictured.

The agent can resize photos for web delivery, write descriptive alt text, add a field-note entry and update GitHub. The website itself has no upload service or automatic photo synchronization.

## Source structure

Put selected web-sized images in `assets/field-notes/`. Add records to `field-notes.js`. The file is intentionally empty until real photos are available; no stock images or fictional visits are presented as field records.

Each entry uses these fields:

```js
{
  title: "A descriptive title for a real visit or activity",
  image: "assets/field-notes/your-selected-photo.webp",
  alt: "Describe what is visible in this particular photo",
  date: "YYYY-MM-DD",
  location: "Optional public place name",
  kind: "Visited inspiration", // or Our activity or Research note
  stage: "Research", // Inspiration, Research, Planned or Approved
  stream: "growing", // learning, growing, land, technology, community, progress
  caption: "What caught our attention",
  learning: "What we learned",
  nextQuestion: "What we want to investigate or try next"
}
```

`kind` describes the evidence: something seen, something tried or a research observation. `stage` describes the related project decision. A visit, photograph or completed activity does not by itself make a project Approved. Confirm permission and a documented decision before applying that stage. A host visit does not establish a partnership.

## Publication

GitHub is public, so published images and captions are public even before GitHub Pages is enabled. Review captions and people pictured before committing. Do not include private location metadata. Photos used on this site should be exported without GPS metadata. Original files can remain in your own photo library.
