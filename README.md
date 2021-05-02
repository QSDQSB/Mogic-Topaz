# QSD's MogicTopaz
>按个人喜好魔改的**蓝色托帕石**主题，适用于Obsidian。
>
>Self-modified **Blue Topaz** Theme for Obsidian.

>Major change includes title color and font, specified as follows.
## Original Link
https://github.com/whyt-byte/Blue-Topaz_Obsidian-css

## Preview
### General Preview
<img width="963" alt="image" src="https://user-images.githubusercontent.com/65840421/116818158-c7f79100-ab61-11eb-9f38-feacde27f44b.png">

### Color From H1 to H6
<img width="855" alt="image" src="https://user-images.githubusercontent.com/65840421/116818188-00976a80-ab62-11eb-8758-a1f3301a4596.png">


### Font
- Main Font: `Charter`, 20px. (at the end of css file)
- Title Font: `SF Pro Rounded`, a MacOS Font.

### Tag
> All tags in the orginal Blue Topaz theme are inheritted. I customised some own tag for my Maths study purposes, including #TBV (To Be Viewed), #MostCrucial, and some other Maths subjects (#Analysis, #MVC, #ProblemSheet, etc). You can search `MostCrucial` in the css file to find the location to DIY tags.
> 
> Some tags use the font `Georgia`.
```css
.tag[href^="#MVC"] {
  font-weight: 600;
  font-family: var(--font-family-h3);
}
.tag[href^="#Groups"] {
  font-weight: 600;
  font-family: var(--font-family-h3);
}
.tag[href^="#MostCrucial"] {
  background-color: #e01493 !important;
  font-weight: 400;
  font-family: "Georgia";
}
.tag[href^="#MostCrucial"]::before {
  content:'⭐️';
  font-size: 20px;
}
.tag[href^="#Analysis"] {
  font-weight: 600;
  font-family: var(--font-family-h3);
}
.tag[href^="#Analysis"]::before {
  content:' 😵';
  font-size: 20px;
}
.tag[href^="#MVC"]::before {
  content:' ☹️';
  font-size: 20px;
}
.tag[href^="#Groups"]::before {
  content:' 🤡';
  font-size: 20px;
}
```

## Notice
- I am not very familiar with how css works, so I might embed some useless rubbish code inside the file when trying to DIY the theme myself.
- Many thanks to the owner of Blue Topaz. This is an amazing theme.
- Hail Hydra.
