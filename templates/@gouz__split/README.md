# Split

This template follows this structure:

```
## Title of the slide .[#@gouz__split/split]

[[left]]

Left part

[[/left]]


and the rest of then content


[[right]]

Right part

[[/right]]

and it can continue here
```

And will render the slide like this:

```
        Title of the slide

Left part         |  Right part
        
          and rest of content
        and it can continue here
```

You can specify Top & Bottom parts too

```
## Title of the slide .[#four-parts]

[[top]]

Content on top

[[/top]]

[[left]]

Left part

[[/left]]


and the rest of then content


[[right]]

Right part

[[/right]]

and it can continue here

[[bottom]]

Content on bottom

[[/bottom]]

and it can continue here
```

And will render the slide like this:

```
            Title of the slide

              Content on top

          Left part  |  Right part

              Content on bottom
              
          and the rest of then content
            and it can continue here
```
