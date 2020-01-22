# Common Accessibility Pitfalls: Climbing out, when you fall in.

---

# What is Accessibility?

---

@quote[Web accesssibility means that people with disabilities can use the web.](www.w3.org/WAI/intro/acccessibility.php)

---

@quote[Web accesssibility means that <strong>EVERYONE</strong> can use the web.](Me)

---

# Why?

@css[text-white fragment](Why should we care about accessibility Chris?)

---

![Group of people](https://images.unsplash.com/photo-1522202176988-66273c2fd55f?ixlib=rb-1.2.1&auto=format&fit=crop&w=1351&q=80)

---

@fa[assistive-listening-systems fa-2x green]&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;@fa[low-vision fa-2x green]&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
@fa[brain fa-2x green]&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
@fa[user-injured fa-2x green]&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
@fa[hands fa-2x green]&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

---

# Problems

---

# Semantic Markup

---

@snap[north-west span-55]

#### Non-semantic

@snap[east span-50 green]

Accessible Markup Examples

@snapend

```html
<div class="...">
  <div class="..." id="...">
    <div class="..."></div>
  </div>
</div>
```

@snapend

@snap[south-west span-55]

#### Semantic

```html
<header>
  <nav>
    <ul>
      <li></li>
      <li></li>
    </ul>
  </nav>
</header>
<main>
  <section></section>
</main>
<footer></footer>
```

@snapend

---

# Alt attributes & images

---

@snap[north-west span-55]

#### Bad Practice

@snap[east span-50 green]

Alt Attribute Examples

@snapend

```html
<img src="..." />
```

@snapend

@snap[south-west span-55]

#### Best Practice

```html
<img src="..." 
     alt="SOMETHING SHORT"/>
```
