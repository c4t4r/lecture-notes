---
title: "hello world"
date: 2023-09-18T07:44:00+07:00
authors: ['Diman Alfon']
tags: ['xx1000']
draft: false
math: true
url: "0048"
---
{{< toc >}}

## first section
Content of first section.

## bold & italics
**bold** *italics*
## link
+ [Google](www.google.com)
+ [Github](www.github.com)

## table
No | Tanggal | Kegiatan | Info
:-: | :- | -: | :-:
1 | 22 Jun | Latihan | -
2 | 15 Jul | UTS | $\frac{x}{y}$
3 | 16 Aug | Praktikum| [Instagram](www.instagram.com/)
4 | 31 Aug | UAS | -
5 | 2 Sep | Remedial | ***nothing***

## list
+ Item
	- dua
	- tiga
+ item lain
+ item lain lagi

## equation

$$
\mathbf{M} =
\left[
\begin{matrix}
1 & 2 & 3 & 4 & 5 \newline
1 & 2 & 3 & 4 & 5 \newline
1 & 2 & y^2 & z & x \newline
\end{matrix}
\right]
$$

$$
x_{1,2} = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
$$

$$\tag{23}
y = ax^2 + bx + c
$$

## flowchart
{{< mermaid >}}
flowchart LR
B --> I --> P --> O --> E
B(("Begin"))
I[/"Input"/]
P["Process"]
O[/"Output"/]
E(("End"))
{{< /mermaid >}}

## svg
{{< html >}}
  <svg style="background: #eee;">
    <rect x="0" y="50" width="50" height="50">
      <animate
        attributeName="x"
        from="0" to="300"
        begin="0s" dur="1s"
        repeatCount="indefinite" />
    </rect>
  </svg>
  {{< /html >}}

  {{< html >}}
  <svg style="background: #eee;" width="500" height="500">
    <rect x="100" y="100" width="100" height="100"></rect>
	<rect x="300" y="100" width="100" height="100"></rect>
	<rect x="200" y="200" width="100" height="150"></rect>
	<rect x="150" y="250" width="50" height="150"></rect>
	<rect x="300" y="250" width="50" height="150"></rect>
  </svg>
  {{<	 /html >}}