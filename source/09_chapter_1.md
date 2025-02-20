\setcounter{page}{1}
\pagenumbering{arabic}
<!-- \doublespacing -->
\linespread{1.63}\selectfont
\setlength{\parindent}{0.1in}

# Introduction, with a citation

## 백그라운드 Background

동해 물과 백두산이 마르고 닳도록 하느님이 보우하사 우리나라 만세
남산 위에 저 소나무 철갑을 두른 듯 바람서리 불변함은 우리 기상일세
가을 하늘 공활한데 높고 구름 없이 밝은 달은 우리 가슴 일편단심일세
이 기상과 이 맘으로 충성을 다하여 괴로우나 즐거우나 나라 사랑하세
무궁화 삼천리 화려 강산 대한 사람 대한으로 길이 보전하세[^fn1]

```java
public class Main {

  public static void main(String[] args) {

    int num = 29;
    boolean flag = false;
    for (int i = 2; i <= num / 2; ++i) {
      // 한글 condition for nonprime number
      if (num % i == 0) {
        flag = true;
        break;
      }
    }

    if (!flag)
      System.out.println(num + " is a prime number.");
    else
      System.out.println(num + " is not a prime number.");
  }
}
```
This is the introduction. Quisque finibus aliquet cursus. Integer in pellentesque tellus. Duis eu dignissim nulla, a porttitor enim. Quisque vehicula leo non ultrices finibus. Duis vehicula quis sem sit amet sollicitudin. Integer neque est, pharetra et auctor vel, iaculis interdum lectus.[^fn2]

<!-- 
To include a reference, add the citation key shown in the references.bib file.
-->

To include a citation to the text, just add the citation key shown in the references.bib file. The style of the citation is determined by the ref_format.csl file. For example, in The Living Sea you can find pictures of the Calypso [@Cousteau1963].

In neque mauris, maximus at sapien a, iaculis dignissim justo. Aliquam erat volutpat. Praesent varius risus auctor est ultricies, sit amet consequat nisi laoreet. Suspendisse non est et mauris pharetra sagittis non porta justo. Praesent malesuada metus ut sapien sodales ornare.

[^fn1]: test
[^fn2]: test

## The middle bit

This is the middle bit. Phasellus quis ex in ipsum pellentesque lobortis tincidunt sed massa. Nullam euismod sem quis dictum condimentum. Suspendisse risus metus, elementum eu congue quis, viverra ac metus. Donec non lectus at lectus euismod laoreet pharetra semper dui. Donec sed eleifend erat, vel ultrices nibh. Nam scelerisque turpis ac nunc mollis, et rutrum nisl luctus.

Duis faucibus vestibulum elit, sit amet lobortis libero. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Sed at cursus nibh. Sed accumsan imperdiet interdum. Proin id facilisis tortor. Proin posuere a neque nec iaculis. Suspendisse potenti. Nullam hendrerit ante mi, vitae iaculis dui laoreet eu.

Cras eleifend velit diam, eu viverra mi volutpat ut. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec finibus leo nec dui imperdiet, tincidunt ornare orci venenatis. Maecenas placerat efficitur est, eu blandit magna hendrerit eu.

### Subsection of the middle bit

This is a subsection of the middle bit. Quisque sit amet tempus arcu, ac suscipit ante. Cras massa elit, pellentesque eget nisl ut, malesuada rutrum risus. Nunc in venenatis mi. Curabitur sit amet suscipit eros, non tincidunt nibh. Phasellus lorem lectus, iaculis non luctus eget, tempus non risus. Suspendisse ut felis mi.

## Summary of chapters

<!-- 
For italic, add _ on either side of the text
For bold, add ** on either side of the text
For bold and italic, add _** on either side of the text
-->

This is a brief outline of what went into each chapter, and a section which shows how to reference headers (which are labelled automatically for you). This chapter, +@sec:introduction-with-a-citation, shows how to use citations and how to reference section headers. \*@sec:literature-review-with-maths shows how use and reference equations. \*@sec:first-research-study-with-code shows how to use and reference code. \*@sec:research-containing-a-figure shows how to use, reference, and resize pdf and jpg figures. \*@sec:research-containing-a-table shows how to use and reference tables. \*@sec:final-research-study is truly revolutionary (but shows nothing functional). **[Appendix 1](#appendix-1-some-extra-stuff)** shows how to add chapters which are not numbered, and has to be referenced manually, as does **[Appendix 2](#appendix-2-some-more-extra-stuff)**. See the base [`README.md`](https://github.com/tompollard/phd_thesis_markdown/blob/master/README.md) for how References are handled - leave `*_references.md` alone, and provide it to `pandoc` last.

Proin faucibus nibh sit amet augue blandit varius.


