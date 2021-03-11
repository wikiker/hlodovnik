# Hlodovník 4.A
## Třída na Gymnáziu Brno, tř. Kpt. Jaroše, p. o.

### Struktura stránky
```
body
	section (tématicky sdružená sekce)
		h1 (nadpis sekce)
		blockquote (samotný container citátů)
```

### Stuktura citátů
1. **citáty bez odpovědi (monologové)**

	```
	<blockquote>
		<em>kontext monologového citátu</em>
		<q>Citát</q><span>autor citátu</span>
	</blockquote>
	```
2. **citáty s odpovědí (dialogové)**

	```
	<blockquote class="dialog">
		<em>kontext dialogového citátu</em>
		<span>autor jedna</span><q>replika jedna</q>
		<span>autor dva</span><q>replika dva</q>
	</blockquote>
	```
	
* Ve všech případech je možné libovolný element vyvolat, stránka by se s tím měla umět vyrovnat.
* Kontext se vykresluje kurzívou.
* Autor se v monologu vykresluje s předcházející pomlčkou, v dialogu se závěrečnou dvojtečkou.

### Font

[CMU Serif](https://fontlibrary.org/en/font/cmu-serif)

* základní font pro všechna využití
* defaultní font při TeXání
