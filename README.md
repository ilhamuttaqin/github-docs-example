# Github Docs Example

## **Step 1 - Using Codeblocks.**

Codeblocks in markdown made it *very easy* for tech people to **copy, paste, share code**
A good _cloud engineer_ uses Codeblocks whenever possible. 

Because it allow others to copy and paste their code to replicate or research issues


- in order to create codeblock in markdown you need to use three backticks ```
- not to confused to quotation '''

```
def factorial(n)
  if n <= 1
    return 1
  else
    return n * factorial(n - 1)
  end
end

# Calculate the factorial of 5
result = factorial(5)
puts "Factorial of 5 is #{result}"
```

- when you can you should attempt to apply syntax highlighting to your codeblocks.

``` ruby
def factorial(n)
  if n <= 1
    return 1
  else
    return n * factorial(n - 1)
  end
end

# Calculate the factorial of 5
result = factorial(5)
puts "Factorial of 5 is #{result}"
```

- make note of where the backtick is placed. 
it should appear above the tab key, but it may vary based on your keyboard layout.
<img width="200px" src="https://github.com/ilhamuttaqin/github-docs-example/assets/109239266/796ceb0b-5107-416c-9048-2718adab3f47" /> 


- Good Cloud Engineers use Cloudblock for both Code and Errors that appear in the console. 

```bash
Traceback (most recent call last):
your_script.rb:1:in `<main>': undefined local variable or method `some_value' for main:Object (NameError)
```
> Here is an example of using codeblocks for an error that appear in the console.


## Step 3 - Use Github Flavored Markdown Track List

- [x] Finish Step 1
- [ ] Finish Step 2
- [x] Finish Step 3
      
Github extends Markdown to have a list where you can check of items.

## Step 4 - Use emojis (optional)

Github Flavored Markdown (GFM) supports emoji shortcodes.
Here some examples ;

| name | shortcode | emoji |
| --- | --- | --- |
| cloud | `:cloud:` | :cloud: |
| cloud with lighting | `:cloud_with_rain:` | :cloud_with_rain: |


## Step 5 - How to create a table.

You can use the following markdown format to create tables.

```markdown
| name | shortcode | emoji |
| --- | --- | --- |
| cloud | `:cloud:` | :cloud: |
| cloud with lighting | `:cloud_with_rain:` | :cloud_with_rain: |
```

Github extends the functionality of markdown table to provide more alignment and table cell formatting options. 

## Reference
- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/)
- [Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#images)
- [GFM-TaskList](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists)
- [GFM-Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet)
- [GFM-Table (with extension)](https://github.github.com/gfm/#tables-extension-)
