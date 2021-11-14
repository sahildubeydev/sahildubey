### Hi there friends👋

<!--
**sahildubey98/sahildubey98** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<!--
- This is **BOLD** and this is **multiple in bold**.
- This is *Italic*

| heading 1 | heading 2 | heading 3 |
| :--- | :---: | ---: |
| row 1 column 1 | row 1 column 2 | row 1 column 3 |

1. item 1
3. item 2
4. item 3

- item 1
  - nested list

- [x] checklist
- [x] checklist
- [x] checklist

This is inline code `const name = 'Sahil Dubey';` with more text

Before
```ts
const firstname = 'Sahil';
const lastname = 'Dubey';
```

After
```ts
const firstname = 'Siya';
const lastname = 'Dubey';
```

OneLine

```diff
- const firstname = 'Sahil';
+ const firstname = 'Siya';
const lastname = 'Dubey';
```

> I think we should go with option 1 of create website

Great idea this discussion was really useful. I will go ahead and do it
-->

<!-- This is a comment -->
<!--
this is the information i want shown

<details>
  <summary>Click for more information</summary>
  This is more description...
  ... 
</details>

    
<img 
   src="https://github-readme-stats.vercel.app/api?username=eddiejaoude&show_icons=true&theme=tokyonight" 
/>

# file .github/workflows/activity.yml
name: Update README

            on:
              schedule:
                - cron: '*/30 * * * *'
              workflow_dispatch:
            
            jobs:
              build:
                runs-on: ubuntu-latest
                name: Update this repo's README with recent activity
            
                steps:
                  - uses: actions/checkout@v2
                  - uses: jamesgeorge007/github-activity-readme@master
                    env:
                      GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

-->

<!--START_SECTION:activity-->
<!--
1. 🎉 Merged PR [#26](https://github.com/jamesgeorge007/csstox/pull/26) in [jamesgeorge007/csstox](https://github.com/jamesgeorge007/csstox)
2. 🎉 Merged PR [#25](https://github.com/jamesgeorge007/csstox/pull/25) in [jamesgeorge007/csstox](https://github.com/jamesgeorge007/csstox)
3. 🎉 Merged PR [#27](https://github.com/jamesgeorge007/csstox/pull/27) in [jamesgeorge007/csstox](https://github.com/jamesgeorge007/csstox)
4. 🎉 Merged PR [#28](https://github.com/jamesgeorge007/csstox/pull/28) in [jamesgeorge007/csstox](https://github.com/jamesgeorge007/csstox)
5. 🎉 Merged PR [#29](https://github.com/jamesgeorge007/csstox/pull/29) in [jamesgeorge007/csstox](https://github.com/jamesgeorge007/csstox)
-->
<!--END_SECTION:activity-->

<!--
- name: GitHub - Activity - Readme
  uses: jamesgeorge007/github-activity-readme@v0.3.6


<table role="table">
  <head>
    <tr>
      <th align="left">Column 1</th>
      <th align="left">Column 2</th>
      <th align="left">Column 3</th>
    </tr>
  </head>
 <tbody>
   <tr>
     <td align="left">
       <ul>
         <li>item 1</li>
         <li>item 2</li>
         <li>item 3</li>
       </ul>
     </td>
     <td align="left">Row 1,Column 2</td>
     <td align="left">Row 1,Column 3</td>
    </tr>
    <tr>
      <td align="left">Row 2, Column 1</td>
      <td align="left">Row 2, Column 2</td>
      <td align="left">Row 2, Column 3</td>
   </tr>
   <tr>
      <td align="left">Row 3, Column 1</td>
      <td align="left">Row 3, Column 2</td>
      <td align="left">Row 3, Column 3</td>
   </tr>
 </tbody>
    
 
 - item 1
 - item 2 **this is bold *italic***
 - item 3 `this is inline code`
-->
