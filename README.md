# Writing Good Documenation
## Step 1 - Using Codeblocks.

Codeblock in markdown make it *very easy* for tech people to **copy, paste, share** code.
A good __Cloud Engineer__ uses Codeblocks whenever possible.

Because it allow others to copy and paste their code to replicate or research issues.

- In order to create codeblocks in markdown you to use three backticks (```)
- No to be confused with qoutation (') [<sub>[1]</sub>](#references)


```
def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end

puts "Enter a number to calculate its factorial:"
num = gets.chomp.to_i

if num < 0
  puts "Factorial is not defined for negative numbers."
else
  result = factorial(num)
  puts "The factorial of #{num} is #{result}."
end
```

- When you can you should attem to applu syntax highlighting your codeblocks

```ruby
def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end

puts "Enter a number to calculate its factorial:"
num = gets.chomp.to_i

if num < 0
  puts "Factorial is not defined for negative numbers."
else
  result = factorial(num)
  puts "The factorial of #{num} is #{result}."
end
```
- Make not of where the backtick button is located.
- It should appear above the tab key, but may vary based on your keyboard layout. 

<img width="200px" src="https://github.com/Robin-MR/github-docs-example/assets/35770296/080b030e-ffb7-4f84-bf6e-30a5e62cda72" />

Good Cloud Engineers use codeblcoks for both code and errors that appear in the console.

```bash
irb(main):001:0> x = 10 / 0
Traceback (most recent call last):
        2: from /usr/bin/irb:11:in `<main>'
        1: from (irb):1
ZeroDivisionError (divided by 0)
```
> Here is an example of using a codeblcok for an error that appear in bash.

## Step 3 - Use Github Flavoured Markdown Task Lists 

Github extens Markdown to have a list where you can check off items.<sub>[3]</sub>

- [x] Finish Step 1
- [x] Finish Step 2
- [ ] Finish Step 3

# Step 4 - Using Emojis (Optional)

GitHub Flavored Markdown GFM supports emoji shortcodes
Here are some examples:
| Name | Shortcode | Emoji |
|-------|--------|-------|
| Cloud | `:cloud:` | :cloud: |
| Cloud with lightning | `:cloud_with_lightning:` | :cloud_with_lightning: |
| Milky Way | `:milky_way:` | :milky_way: |

# Step 5 how to create a table

You can use the following markdown format to create tables:

```md
| Name | Shortcode | Emoji |
|-------|--------|-------|
| Cloud | `:cloud:` | :cloud: |
| Cloud with lightning | `:cloud_with_lightning:` | :cloud_with_lightning: |
| Milky Way | `:milky_way:` | :milky_way: |
```
Github extens the functionality of Markdown tables to provide more alignment and table cell formatting options.[<sub>[4]</sub>](#references)

## References 
- [Basic writing and formatting syntax
](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)<sub>[1]</sub>
- [Headings](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#headings)<sub>[2]</sub>]
- [GFM - Wrting](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#quoting-text)<sub>[3]</sub>
- [GFM - Emoji Cheatsheet]([thub/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#using-emoji](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)
- [GFM - Tabels (with extentions)](https://github.github.com/gfm/#tables-extension-)<sub>[4]</sub>
