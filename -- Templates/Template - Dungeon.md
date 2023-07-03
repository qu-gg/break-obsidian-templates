---
Seed: 233
---
#Dungeon
```dataviewjs 
await dv.el("div", "", { cls: "container-root" }); 
const container = document.querySelectorAll('.container-root')[0]; 
container.innerHTML = `<iframe height="800" width="75%" src="https://watabou.github.io/one-page-dungeon/?seed=${dv.current().file.frontmatter.Seed}" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>`; 
await dv.el("div", container); 
```
**Name**:
**Location**:
**Enemies**:
