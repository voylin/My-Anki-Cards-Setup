# My-Anki-Cards-Setup

# Japanese Note Cards:
## Kanji + Kana = Meaning
### Front Template:
{{Kanji}}
{{#Kana}}<br>{{Kana}}{{/Kana}}

### Styling:
.card {
 font-family: source han sans jp;
 font-size: 60px;
 text-align: center;
 color: black;
background-color: white;
}

### BackTemplate:
{{FrontSide}}
<hr id=answer>
{{Meaning}}

## Meaning = Kanji+Kana:
### Front Template:
{{Meaning}}

### Back Template:
{{FrontSide}}
<hr id=answer>
{{Kanji}}
{{#Kana}}<br>{{Kana}}{{/Kana}}




# Kanji Note Cards:
## Kanji = Meaning:
### Front Template:
<div class='kanji'>{{Kanji}}</div>

### Styling:
.card {
 font-family: source han sans jp;
 font-size: 50px;
 text-align: center;
 color: black;
background-color: white;
}
.kanji{
font-size: 90px;
}

### Back Template:
{{FrontSide}}
<hr id=answer>
{{Meaning}}

## Meaning = Kanji:
### Front Template:
{{Meaning}}

### BackTemplate:
{{FrontSide}}
<hr id=answer>
<div class='kanji'>{{Kanji}}</div>
