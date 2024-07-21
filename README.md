# mark\_test 123

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

> ttest 13

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td></td><td>ggg</td><td></td></tr><tr><td></td><td></td><td></td></tr><tr><td></td><td></td><td>fff</td></tr></tbody></table>

```stl
solid cube_corner
  facet normal 0.0 -1.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 1.0 0.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
  facet normal 0.0 0.0 -1.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 1.0 0.0 0.0
    endloop
  endfacet
  facet normal -1.0 0.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 0.0 1.0
      vertex 0.0 1.0 0.0
    endloop
  endfacet
  facet normal 0.577 0.577 0.577
    outer loop
      vertex 1.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
endsolid
```





## Introducing Novel

[Novel](https://github.com/steven-tey/novel) is a Notion-style WYSIWYG editor with AI-powered autocompletion. Built with [Tiptap](https://tiptap.dev/) + [Vercel AI SDK](https://sdk.vercel.ai/docs).

### Installation

```
npm i novel
```

### Usage

### dsadas

**dsdsI**

```
import { Editor } from "novel";

export default function App() {
  return (
     <Editor />
  )
}
```

### Features

1. Slash menu & bubble menu
2. AI autocomplete (type `++` to activate, or select from slash menu)
3. Image uploads (drag & drop / copy & paste, or select from slash menu) 
4. Add tweets from the command slash menu:

   [twitter]
5. Mathematical symbols with LaTeX expression:
   1. [math]
   2. [math]
   3. [math]
   4. [math]
   5. [math]

![banner.png](https://public.blob.vercel-storage.com/pJrjXbdONOnAeZAZ/banner-2wQk82qTwyVgvlhTW21GIkWgqPGD2C.png "banner.png")---

### Learn more

- [ ] Star us on [GitHub](https://github.com/steven-tey/novel)

- [ ] Install the [NPM package](https://www.npmjs.com/package/novel)

- [ ] [Deploy your own](https://vercel.com/templates/next.js/novel) to Vercel
