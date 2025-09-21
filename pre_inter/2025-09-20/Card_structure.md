### Front:

```
<div class="card typed-card">
  <div class="front">
    {{Front}}
  </div>
  <div class="typed-input">
    {{type:Back}}
  </div>
	<div class="audio-plyer">
		<audio controls preload="none" src={{Audio}}></audio>
	</div>
</div>
```

### Back:

```
<div class="card typed-card back-side">
	
	{{FrontSide}}

	<hr id=answer>

</div>
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

.audio-plyer{
margin-top: 24px
}

.back-side{}
```