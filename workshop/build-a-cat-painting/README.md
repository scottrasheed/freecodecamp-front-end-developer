# CSS Cat Painting

I built a cat illustration with HTML and CSS while working through freeCodeCamp’s 80-step Cat Painting workshop. The project uses CSS borders, gradients, and transforms to draw the cat’s face, ears, and whiskers.

## Run locally

1. Keep `index.html` and `styles.css` in the same folder.
2. Open `index.html` in your browser.

The page runs offline and requires no installation.

## Project files

- `index.html` contains the structure of the cat’s face.
- `styles.css` draws and positions each feature.

<details>
<summary>Show workshop notes</summary>

| Steps | What I practiced |
| --- | --- |
| 1–16 | Linking a stylesheet, testing CSS positioning, and centering the cat’s head |
| 17–38 | Drawing triangles with borders, rotating the ears, and layering them with `z-index` |
| 39–50 | Shaping the eyes with `border-radius` and positioning their highlights |
| 51–62 | Drawing the nose and using elliptical borders for the mouth |
| 63–80 | Styling all six whiskers with descendant selectors and positioning them with offsets and rotations |

The numbered comments in `index.html` and `styles.css` show where each step fits. For example, Step 80 adds the final rotation to the bottom-right whisker.

```css
.cat-whisker-right-bottom {
  position: absolute;
  top: 134px;
  left: 109px;
  transform: rotate(3deg);
}
```

</details>

## Credits

Built as part of the [freeCodeCamp Cat Painting workshop](https://github.com/freeCodeCamp/freeCodeCamp/tree/main/curriculum/challenges/english/blocks/workshop-cat-painting).