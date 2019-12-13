## Diff

Unterschiede zwischen Texten anzeigen

Notes:
- engl. kurz für "difference" (Unterschied)

---

<div class="columns">

<div class="col">
<pre style="white-space: pre-wrap; border: none; box-shadow: none">
Regierungen der Industriellen Welt, ihr müden Riesen aus Fleisch und Stahl, ich komme aus dem Cyberspace, dem neuen Zuhause des Geistes.
Als Vertreter der Zukunft bitte ich euch aus der Vergangenheit, uns in Ruhe zu lassen.
Ihr seid nicht willkommen unter uns.
Ihr habt keine Souveränität, wo wir uns versammeln.
</pre>
</div>

<div class="col">
<pre style="white-space: pre-wrap; border: none; box-shadow: none">
Regierungen der Industriellen Welt, ihr müden Riesen aus Fleisch und Stahl, ich komme aus dem Cyberspace, dem neuen Zuhause des Geistes.
Als Verterter der Zukunft bitte ich euch aus der Vergangenheit, uns in Ruhe zu lassen.
Ihr seid nicht willkommen unter uns.
Ihr habt keine Souveränität, wo wir uns versammeln.
</pre>
</div>

</div>

Notes:
- Eine Unabhängigkeitserklärung des Cyberspace (englischer Originaltitel: A Declaration of the Independence of Cyberspace) von John Perry Barlow

---

`diff -u cyber.txt.orig cyber.txt`

Notes:
- "lhs" (left hand side) <-> "rhs" (right hand side)
- alt <-> neu

---

```diff
--- cyber.txt.orig	2019-12-12 12:42:41.000000000 +0100
+++ cyber.txt	2019-12-12 12:42:47.000000000 +0100
@@ -1,4 +1,4 @@
 Regierungen der Industriellen Welt, ihr müden Riesen aus Fleisch und Stahl, ich komme aus dem Cyberspace, dem neuen Zuhause des Geistes.
-Als Vertreter der Zukunft bitte ich euch aus der Vergangenheit, uns in Ruhe zu lassen.
+Als Verterter der Zukunft bitte ich euch aus der Vergangenheit, uns in Ruhe zu lassen.
 Ihr seid nicht willkommen unter uns.
 Ihr habt keine Souveränität, wo wir uns versammeln.
```
<!-- .element style="white-space: pre-wrap;" -->

---

<!-- .element data-background="white" -->

<div class="mergely-full-screen-8 stretch" style="font-size: 0.7em">
	<div class="mergely-resizer">
		<div id="mergely"></div>
	</div>
</div>

---

### Tools

- [Meld](https://meldmerge.org/)
- FileMerge (nur macOS, aber in Xcode enthalten)
- [KDiff3](http://kdiff3.sourceforge.net/)
- [WinMerge](https://winmerge.org/)
