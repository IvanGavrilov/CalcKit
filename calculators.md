---
layout: page
homepage: false
isHome: false
title: "Calculators"
---

# Introduction

---

**Calculators** are the main type of tools within CalcKit. They are very easy to build and represent the largest portion of tools in **CalcKit**

Below I'll try to explain all components of the **calculators** and how to build them, with some examples.

To create a new calculator, open the `My Tools` folder, click the `⋮` and then click [`Create New Calculator`](https://app.calckit.io/create/converter)

# Components

---

Each calculator is built using multiple required and optional components.

`Icon` `Title` `Category` `Tags` `Header` `Footer` `Image` `Image Description` `Options` `Variables`

The only required components are `Icon`, `Title` and `Variables`.

## Icon / Title / Category / Tags

---

![Icon Title Category Tags](https://raw.githubusercontent.com/IvanGavrilov/calckit/master/images/icon_title_category_tags.png)

The **Title** and the **Icon** are self-explanatory.

The **Icon** can be changed by simply clicking on it. After you click it, a window will pop-up where you'll see a list with pre-made icons to choose from and also a field where you can type URL to your own icon.

The **Category** could be useful when you add multiple calculators from different branches in the same folder and you want to know to which branche each of them belongs. Take for example our [Library](https://app.calckit.io/library). There are over one-hundred calculators in it, for mathematics, electronics, converters and so on. To find all electronics calculators you would, for example, type `Electronics` in the Search Bar and only the electronics tools will be displayed.

The **Tags** *(separated by space)* are also used for searching, but *(unlike the Title and Category)* they are not visible to the user. Using a correct combination of tags you can create some very nice search queries. For example, in the `Length` converter we have added the units `km` `m` `cm` etc. in the tags and we've also included the word `to`. Now, when you open the [Library](https://app.calckit.io/library) and search for `km to cm` the `Length` converter will be right there on top.

## Header / Footer

---

![Header Footer](https://raw.githubusercontent.com/IvanGavrilov/calckit/master/images/header_footer.png)

The **Header** is a text box displayed on the top of your calculator, above the image and variables.

The **Footer** is a text box displayed on the bottom of your calculator, below the variables.

Both **Header** and **Footer** are optional fields. If you leave them empty, they will automatically be hidden in your calcualator.

Both fields can contain one or multiple lines of text.

You can also apply some basic styling on the text *(as you can see on the image above)* making portions of it `**bold**`, `//italic//` or `__underlined__`, or also mixing them `**//__together__//**`.

## Image / Image Description

---

...
