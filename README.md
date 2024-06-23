## 🚀 Key Takeaways

### ➡️Accessing first right neighbour
```css

.list .item:hover + * {
    filter: brightness(0.6);
    transform: translateZ(100px) rotateY(30deg);
}
```
In the same way,

### ➡️Accessing second right neighbour

```css
.list .item:hover + * + * {
    filter: brightness(0.4);
    transform: translateZ(70px) rotateY(20deg);
}
```
### ➡️For accessing left first neighbour
```css
.list .item:has(+ *:hover) {
    filter: brightness(0.6);
    transform: translateZ(100px) rotateY(-30deg);
}
```
In the same way,

### ➡️For accessing left first neighbour

```css
.list .item:has(+ * + *:hover) {
    filter: brightness(0.4);
    transform: translateZ(70px) rotateY(-20deg);
}
```
## 🎯CSS properties I have used first time

1. `transform-style: preserve-3d;`
2. `transform: perspective(1000px);`
3. `grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));`
4. `filter: brightness(0.2);`
5. `transform: translateZ(30px) rotateY(-10deg);`

## 🎬 Video
https://github.com/mutant1o1/image-hover_effect/assets/102402426/ff666c4f-85b9-49d5-addb-5a3af84dc8e0

