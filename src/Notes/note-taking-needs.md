---
id: note-taking-needs
aliases: []
tags:
  - notes
---

# Note Taking Needs

1. Browse
   Browse all notes because I don't know what I wrote a long time a go and I can't search for what I'm not aware of.
2. Search
3. View a note
   1. basic markdown
   2. mermaid
   3. charts
   4. import partials?
4. Higher order notes
   1. dataview like queries
   2. index / maps of content generation
5. Templates
6. Journal
   1. journal specific template
   2. search just journal
   3. create journal entry from a calendar
   4. open a journal entry from a calendar
7. Export PDF or HTML for sharing

## Mermaid

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

## Code

```rust
let greeting = "World";
println!("Hello, {}!", greeting);
```

## Charts

```echarts
{
  xAxis: {
    data: ['A', 'B', 'C', 'D', 'E']
  },
  yAxis: {},
  series: [
    {
      data: [10, 22, 28, 43, 49],
      type: 'bar',
      stack: 'x'
    },
    {
      data: [5, 4, 3, 5, 10],
      type: 'bar',
      stack: 'x'
    }
  ]
};
```

## Queries

### tree

```bash
<!-- cmdrun tree ../Journal -->
```

### Rust

#### Depending on Shebang

<!-- cmdrun ../../bin/hello.rs -->

#### Using rustc and --out-dir

<!-- cmdrun rustc ../../bin/hello.rs --out-dir ../../.cache; ../../.cache/hello; rm ../../.cache/hello -->
