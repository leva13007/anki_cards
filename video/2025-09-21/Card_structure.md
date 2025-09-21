### Front:

```
<video controls autoplay width="600">
  <source src="{{VideoFilename}}" type="video/webm">
</video>

{{type:Front}}
```

### Back:

```
<video controls autoplay width="600">
  <source src="{{VideoFilename}}" type="video/webm">
</video>

{{type:Back}}

</hr>

<div class="ua-answer">
{{Back}}
</div
```

### Styles

```
.card{
	margin: 32px;
	font-size: 28px !important;
}

hr#answer {
  margin-bottom: 20px;
}

input#typeans{
	font-size: 28px !important;
}

#typeans > span{
font-size: 28px !important;
}


.typed-input input[type="text"],
.typed-input input[type="text"]:focus,
.typed-input input,
.typed-input textarea {
  margin-top: 24px;
  font-size: 46px;
  padding: 8px 12px;
  width: 100%;
  border: 2px solid #aaa;
  border-radius: 6px;
  box-sizing: border-box;
  outline: none;
  transition: border 0.3s ease;
}

.typed-input input[type="text"]:focus {
  border-color: #007acc;
}

.ua-answer{
border-top: 1px solid white;
margin-top: 24px;
padding-top: 24px;
}
```