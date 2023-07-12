<template>
  <Header />
  <main>
    <h1 class="title-content">Buttons</h1>
    <div class="buttons-styles-section">
      <ul class="buttons-styles-list" id="default">
        <li class="button-style-item">
          <span class="style-name">Button</span>
          <!-- <Button :stylesClasses="['default']" /> -->
          <Button class="default" />
        </li>
        <li class="button-style-item">
          <span class="style-name">&:hover, &:focus</span>
          <!-- <Button :stylesClasses="['default', 'on-hover', 'on-focus']" /> -->
          <Button class="default on-hover on-focus" />
        </li>
      </ul>

      <ul class="buttons-styles-list" id="outline">
        <li class="button-style-item">
          <span class="style-name">Outline</span>
          <!-- <Button :stylesClasses="['outline']" /> -->
          <Button class="outline" />
        </li>
        <li class="button-style-item">
          <span class="style-name">&:hover, &:focus</span>
          <!-- <Button :stylesClasses="['outline', 'on-hover', 'on-focus']" /> -->
          <Button class="outline on-hover on-focus" />
        </li>
      </ul>

      <ul class="buttons-styles-list" id="text">
        <li class="button-style-item">
          <span class="style-name">Text</span>
          <!-- <Button :stylesClasses="['only-text']" /> -->
          <Button class="only-text" />
        </li>
        <li class="button-style-item">
          <span class="style-name">&:hover, &:focus</span>
          <!-- <Button :stylesClasses="['only-text', 'on-hover', 'on-focus']" /> -->
          <Button class="only-text on-hover on-focus" />
        </li>
      </ul>

      <ul class="buttons-styles-list" id="disable-shadow">
        <li class="button-style-item">
          <span class="style-name">Disable shadow</span>
          <!-- <Button :stylesClasses="['disable-shadow']" /> -->
          <Button class="disable-shadow" />
        </li>
      </ul>

      <ul class="buttons-styles-list" id="disabled">
        <li class="button-style-item">
          <span class="style-name">Disabled</span>
          <!-- <Button :stylesClasses="['disabled']" /> -->
          <Button class="disabled" />
        </li>
        <li class="button-style-item">
          <span class="style-name">Disabled only text</span>
          <!-- <Button :stylesClasses="['disabled', 'only-text']" /> -->
          <Button class="disabled only-text" />
        </li>
      </ul>

      <ul class="buttons-styles-list" id="with-icon">
        <li class="button-style-item">
          <span class="style-name">Start icon</span>
          <!-- <Button :stylesClasses="['w-icon', 'startIcon']" :icon="'shopping_cart'" /> -->
          <Button class="w-icon startIcon" :icon="'🛒'" />
        </li>
        <li class="button-style-item">
          <span class="style-name">End icon</span>
          <!-- <Button :stylesClasses="['w-icon', 'endIcon']" :icon="'shopping_cart'" /> -->
          <Button class="w-icon endIcon" :icon="'🛒'" />
        </li>
      </ul>

      <ul class="buttons-styles-list" id="sizes-buttons">
        <li class="button-style-item">
          <span class="style-name">Size small</span>
          <!-- <Button :stylesClasses="['s-sm', 'bg-primary', 'borderless', 'b-round-6', 'txt-white']" /> -->
          <Button class="s-sm bg-primary borderless b-round-6 txt-white" />
        </li>

        <li class="button-style-item">
          <span class="style-name">Size medium</span>
          <!-- <Button :stylesClasses="['s-md', 'bg-primary', 'borderless', 'b-round-6', 'txt-white']" /> -->
          <Button class="s-md bg-primary borderless b-round-6 txt-white" />
        </li>

        <li class="button-style-item">
          <span class="style-name">Size large</span>
          <!-- <Button :stylesClasses="['s-lg', 'bg-primary', 'borderless', 'b-round-6', 'txt-white']" /> -->
          <Button class="s-lg bg-primary borderless b-round-6 txt-white" />
        </li>
      </ul>

      <ul class="buttons-styles-list" id="colors-buttons">
        <li class="button-style-item">
          <span class="style-name">Color default</span>
          <!-- <Button :stylesClasses="['s-sm', 'bg-default', 'borderless', 'b-round-6', 'txt-dark']" /> -->
          <Button class="s-sm bg-default borderless b-round-6 txt-dark" />
        </li>
        <li class="button-style-item">
          <span class="style-name">Color primary</span>
          <!-- <Button :stylesClasses="['s-sm', 'bg-primary', 'borderless', 'b-round-6', 'txt-white']" /> -->
          <Button class="s-sm bg-primary borderless b-round-6 txt-white" />
        </li>
        <li class="button-style-item">
          <span class="style-name">Color secondary</span>
          <!-- <Button :stylesClasses="['s-sm', 'bg-secondary', 'borderless', 'b-round-6', 'txt-white']" /> -->
          <Button class="s-sm bg-secondary borderless b-round-6 txt-white" />
        </li>
        <li class="button-style-item">
          <span class="style-name">Color danger</span>
          <!-- <Button :stylesClasses="['s-sm', 'bg-danger', 'borderless', 'b-round-6', 'txt-white']" /> -->
          <Button class="s-sm bg-danger borderless b-round-6 txt-white" />
        </li>
      </ul>

      <ul class="buttons-styles-list" id="colors-buttons-hover-and-focus">
        <li class="button-style-item">
          <span class="style-name">&:hover, &:focus</span>
          <!-- <Button :stylesClasses="['s-sm', 'bg-default', 'borderless', 'b-round-6', 'txt-dark', 'on-focus' -->
          <Button class="s-sm bg-default borderless b-round-6 txt-dark on-focus on-hover" />
        </li>
        <li class="button-style-item">
          <span class="style-name">&:hover, &:focus</span>
          <!-- <Button :stylesClasses="['s-sm', 'bg-primary', 'borderless', 'b-round-6', 'txt-white', 'on-focus' -->
          <Button class="s-sm bg-primary borderless b-round-6 txt-white on-focus on-hover" />
        </li>
        <li class="button-style-item">
          <span class="style-name">&:hover, &:focus</span>
          <!-- <Button :stylesClasses="['s-sm', 'bg-secondary', 'borderless', 'b-round-6', 'txt-white', 'on-focus' -->
          <Button class="s-sm bg-secondary borderless  b-round-6 txt-white on-focus on-hover" />
        </li>
        <li class="button-style-item">
          <span class="style-name">&:hover, &:focus</span>
          <!-- <Button :stylesClasses="['s-sm', 'bg-danger', 'borderless', 'b-round-6', 'txt-white', 'on-focus' -->
          <Button class="s-sm bg-danger borderless b-round-6 txt-white on-focus on-hover" />
        </li>
      </ul>
    </div>
    <span class="icon-link">
      Icons: https://material.io/resources/icons/?style=round
    </span>
  </main>
  <footer>created by Nehuen - devChallenges.io</footer>
</template>

<script>
import Header from './components/UI/Header.vue';
import Button from './components/UI/Button.vue';
export default {
  name: 'App',
  components: {
    Header,
    Button
  }
}
</script>

<style>


#app {
  width: 100%;
  height: auto;
  padding: 5vh 0;
  display: grid;
  grid-template-columns: 20% 80%;
  grid-auto-rows: auto;
  grid-template-areas: 
    "header content"
    "header footer";
}

main {
  grid-area: content;
  padding: 3vh 0;
}

main .title-content {
  font: 500 1.5rem 'Poppins', sans-serif;
  color: #4F4F4F;
}

.buttons-styles-section {
  display: flex;
  flex-direction: column;
  row-gap: 5vh;
}

ul.buttons-styles-list {
  width: 100%;
  display: flex;
  flex-wrap: wrap;
  gap: 3vh 2vw;
}

.buttons-styles-list li.button-style-item {
  display: flex;
  flex-direction: column;
  row-gap: 1vh;
}

li.button-style-item .style-name {
  font: 400 14px 'Ubuntu Mono', monospace;
}

.icon-link {
  font: 400 12px 'Ubuntu Mono', monospace;;
  color: #828282;
}

footer {
  grid-area: footer;
  color: #A9A9A9;
  font: 700 14px 'Montserrat', sans-serif;
}
</style>
