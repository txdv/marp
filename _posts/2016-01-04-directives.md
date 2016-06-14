---
category: top
---

<div class="col-xs-12" markdown="1">

# Directives

Marp's Markdown has extended directives to affect slides. Insert HTML comment as `<!-- {directive_name}: {value} -->`

</div>
<div class="col-xs-12 col-sm-6" markdown="1">

## Pagination

Want you pagination? Insert `<!-- page_number: true -->` to top.

If you want to exclude first page number, move directive to after first ruler.

```markdown
# First page

The page number `1` can not see.

---
<!-- page_number: true -->

# Second page

The page number `2` can see!
```

</div>
<div class="col-xs-12 col-sm-6" markdown="1">

## Resize slide

You can resize slide by Global Directive `$size`.
Insert `<!-- $size: 16:9 -->` if you want to display slides on 16:9 screen. That’s all!

```html
<!-- $size: 16:9 -->
```

`$size` directive supports `4:3`, `16:9`, `A0`-`A8`, `B0`-`B8` and suffix of `-portrait`.

Marp also supports `$width` and `$height` directives to set custom size.

</div>
<div class="col-xs-12" markdown="1">

---

Want you the example? Let's see [example.md](https://raw.githubusercontent.com/yhatt/marp/master/example.md){:target="_blank"}.

</div>