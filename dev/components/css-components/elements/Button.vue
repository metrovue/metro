
<template>
<div class="container">
    <h1 class="title">Buttons</h1>
    <h2 class="subtitle">
      The classic <strong>button</strong>, in different colors, sizes, and states
    </h2>

    <hr>

    <div class="columns">
      <div class="column">
        <div class="block">
          <a class="button">Button</a>
          <a class="button is-white">White</a>
          <a class="button is-light">Light</a>
          <a class="button is-dark">Dark</a>
          <a class="button is-black">Black</a>
          <a class="button is-link">Link</a>
        </div>
        <div class="block">
          <a class="button is-primary">Primary</a>
          <a class="button is-info">Info</a>
          <a class="button is-success">Success</a>
          <a class="button is-warning">Warning</a>
          <a class="button is-danger">Danger</a>
        </div>
      </div>
      <div class="column">

      </div>
    </div>

    <hr>

    <h3 class="title">Sizes</h3>

    <div class="columns">
      <div class="column">
        <a class="button is-small">Small</a>
        <a class="button">Normal</a>
        <a class="button is-medium">Medium</a>
        <a class="button is-large">Large</a>
      </div>
      <div class="column">
		  
      </div>
    </div>

    <hr>

    <h3 class="title">Styles</h3>
    <h4 class="subtitle">Outlined</h4>

    <div class="columns">
      <div class="column">
        <a class="button is-outlined">Outlined</a>
        <a class="button is-primary is-outlined">Outlined</a>
        <a class="button is-info is-outlined">Outlined</a>
        <a class="button is-success is-outlined">Outlined</a>
        <a class="button is-danger is-outlined">Outlined</a>
      </div>
      <div class="column">
      </div>
    </div>

    <h4 class="subtitle">Inverted (the text color becomes the background color, and vice-versa)</h4>

    <div class="columns">
      <div class="column">
        <div class="notification is-primary">
          <a class="button is-primary is-inverted">Inverted</a>
          <a class="button is-info is-inverted">Inverted</a>
          <a class="button is-success is-inverted">Inverted</a>
          <a class="button is-danger is-inverted">Inverted</a>
        </div>
      </div>
      <div class="column">
      </div>
    </div>

    <hr>

    <h3 class="title">States</h3>
    <h4 class="subtitle">Loading</h4>

    <div class="columns">
      <div class="column">
        <a class="button is-loading">Loading</a>
        <a class="button is-primary is-loading">Loading</a>
        <a class="button is-info is-loading">Loading</a>
        <a class="button is-success is-loading">Loading</a>
        <a class="button is-warning is-loading">Loading</a>
        <a class="button is-danger is-loading">Loading</a>
      </div>
      <div class="column">
      </div>
    </div>

    <h4 class="subtitle">Active</h4>

    <div class="columns">
      <div class="column">
        <a class="button is-active">Active</a>
        <a class="button is-primary is-active">Active</a>
        <a class="button is-info is-active">Active</a>
        <a class="button is-success is-active">Active</a>
        <a class="button is-warning is-active">Active</a>
        <a class="button is-danger is-active">Active</a>
      </div>
      <div class="column">
      </div>
    </div>

    <h4 class="subtitle">Disabled</h4>

    <div class="columns">
      <div class="column">
        <a class="button is-disabled">Disabled</a>
        <a class="button is-primary is-disabled">Disabled</a>
        <a class="button is-info is-disabled">Disabled</a>
        <a class="button is-success is-disabled">Disabled</a>
        <a class="button is-warning is-disabled">Disabled</a>
        <a class="button is-danger is-disabled">Disabled</a>
      </div>
      <div class="column">
      </div>
    </div>

    <h4 class="subtitle">With Font Awesome icons</h4>

    <div class="columns">
      <div class="column">
        <p class="control">
          <a class="button">
            <span class="icon">
              <i class="fa fa-github"></i>
            </span>
            <span>GitHub</span>
          </a>
          <a class="button is-primary">
            <span class="icon">
              <i class="fa fa-twitter"></i>
            </span>
            <span>Twitter</span>
          </a>
          <a class="button is-success">
            <span class="icon is-small">
              <i class="fa fa-check"></i>
            </span>
            <span>Save</span>
          </a>
          <a class="button is-danger is-outlined">
            <span>Delete</span>
            <span class="icon is-small">
              <i class="fa fa-times"></i>
            </span>
          </a>
        </p>
        <p class="control">
          <a class="button is-small">
            <span class="icon is-small">
              <i class="fa fa-github"></i>
            </span>
            <span>GitHub</span>
          </a>
          <a class="button">
            <span class="icon">
              <i class="fa fa-github"></i>
            </span>
            <span>GitHub</span>
          </a>
          <a class="button is-medium">
            <span class="icon">
              <i class="fa fa-github"></i>
            </span>
            <span>GitHub</span>
          </a>
          <a class="button is-large">
            <span class="icon is-medium">
              <i class="fa fa-github"></i>
            </span>
            <span>GitHub</span>
          </a>
        </p>
      </div>
      <div class="column">
		  
      </div>
    </div>

    <hr>

    <h3 class="title">Button group</h3>
    <div class="content">
      <p>If you want to <strong>group</strong> buttons together, use the <code>is-grouped</code> modifier on the <code>control</code> container:</p>
    </div>
    <div class="example">
      <div class="control is-grouped">
        <p class="control">
          <a class="button is-primary">
            Save changes
          </a>
        </p>
        <p class="control">
          <a class="button">
            Cancel
          </a>
        </p>
        <p class="control">
          <a class="button is-danger">
            Delete post
          </a>
        </p>
      </div>
    </div>

    <hr>

    <h3 class="title">Button addons</h3>
    <div class="content">
      <p>If you want to use buttons as <strong>addons</strong>, use the <code>has-addons</code> modifier on the <code>control</code> container:</p>
    </div>
    <div class="example">
      <p class="control has-addons">
        <a class="button">
          <span class="icon is-small">
            <i class="fa fa-align-left"></i>
          </span>
          <span>Left</span>
        </a>
        <a class="button">
          <span class="icon is-small">
            <i class="fa fa-align-center"></i>
          </span>
          <span>Center</span>
        </a>
        <a class="button">
          <span class="icon is-small">
            <i class="fa fa-align-right"></i>
          </span>
          <span>Right</span>
        </a>
      </p>
    </div>

  </div>
</section>

</div>

</template>

<script>
export default {
  data () {
    return {

    }
  }
}
</script>

