# tiptap-extension-trailing-node

<h3 align="center">
    The extension adds an actual node to the tiptap content.
    Add a blank node after the node to solve the problem of not being able to append content.
</h3>

<br/>

<p align="center">
  <a href="https://www.npmjs.com/package/tiptap-extension-trailing-node">
    <img
     alt="NPM URL"
     src="https://img.shields.io/badge/npm-tiptapExtensionTrailingNode?logo=npm">
  </a>
  <img
     alt="version"
     src="https://img.shields.io/badge/version-1.0.0-blue">
</p>

<br>

---

## Install

```shell
npm install tiptap-extension-trailing-node -S
```

## Usage

```js
import TrailingNode from "tiptap-extension-trailing-node";

const editor = new Editor({
  element: document.querySelector(".editor"),
  extensions: [StarterKit, TrailingNode],
});
```

## Relations

**tiptap-Trailing Node:** https://tiptap.dev/docs/editor/experiments/trailing-node

**tiptap-appmsg-editor:** https://github.com/KID-1912/tiptap-appmsg-editor
