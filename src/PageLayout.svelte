<script>
  import { Route } from 'svelte-router-spa'
  export let currentRoute
  const params = {}
</script>

<style>
.headerbar {
    display: block;
    width: 100%;
    margin: 0;
    background-color: rgb(116, 73, 0);
    font-size: 1.25rem;
    color: white;
    text-decoration: none;
    box-sizing: border-box;
    padding: 13px 39px;
}

.headerbar * {
    color: inherit;
    line-height: 30px;
    text-decoration: inherit;
    font-weight: bold;
}

@media (min-width: 768px) {
    .container {
        margin-top: 48px;
        margin-left: auto;
        margin-right: auto;
        max-width: 728px;
    }
}

@media (max-width: 767px) {
    .container {
        margin-top: 20px;
        margin-left: 20px;
        margin-right: 20px;
    }
}
</style>

<div class="headerbar">
<a href="/">Query string bug</a>
</div>
<div class="container">
Demo of <a href="https://github.com/jorgegorka/svelte-router/issues/33">svelte-router bug #33</a>.
</div>