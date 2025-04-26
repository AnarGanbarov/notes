---
title: Добро пожаловать
nav_order: 1
---

# Добро пожаловать!

Выберите нужный раздел в меню слева.

# Поиск по сайту
{% raw %}
<div id="search"></div>
<link href="https://unpkg.com/pagefind/pagefind-ui.css" rel="stylesheet">
<script src="https://unpkg.com/pagefind/pagefind-ui.js"></script>

<script>
  window.addEventListener('DOMContentLoaded', (event) => {
    new PagefindUI({
      element: "#search",
      showImages: false,
      resetStyles: false,
      translations: {
        placeholder: "Искать...",
        button: "Поиск",
        noResults: "Ничего не найдено",
        result: {
          result: "результат",
          results: "результатов"
        }
      }
    });
  });
</script>

<style>
  #search {
    margin-top: 2rem;
    margin-bottom: 2rem;
  }
  .pagefind-ui__search-input {
    width: 100%;
    max-width: 500px;
    padding: 0.5rem;
    font-size: 1rem;
    border-radius: 8px;
    border: 1px solid #ccc;
  }
  .pagefind-ui__result {
    margin-top: 1rem;
    padding: 1rem;
    border-radius: 8px;
    border: 1px solid #eee;
    background: #f9f9f9;
  }
</style>
{% endraw %}