# GitHub Markdown

Here are a few markdown additions for GitHub Markdown.

## Blockquotes

### Badges

you can use these additional badges to give your makrdown more structure and statement. The badges are always `21px` high and `100px` wide. The SVG consists of the symbol and the text behind it. You can find the Octicon symbols [here](https://primer.style/octicons/). The fontstack I used can be found [here](https://primer.style/design/foundations/typography#font-stack).

#### Info Badge

```markdown
[badge-info]: https://github.com/Mqxx/GitHub-Markdown/blob/main/blockquotes/badge/dark-theme/info.svg 'Info'

> ![badge-info][badge-info]<br>
> Info
```
[badge-info]: https://github.com/Mqxx/GitHub-Markdown/blob/main/blockquotes/badge/dark-theme/info.svg 'Info'

> ![badge-info][badge-info]<br>
> Info

<br>

#### Example Badge

```markdown
[badge-info]: https://github.com/Mqxx/GitHub-Markdown/blob/main/blockquotes/badge/dark-theme/example.svg 'Example'

> ![badge-example][badge-example]<br>
> Example
```
[badge-example]: https://github.com/Mqxx/GitHub-Markdown/blob/main/blockquotes/badge/dark-theme/example.svg 'Example'

> ![badge-example][badge-example]<br>
> Example

<br>

#### Tip Badge

```markdown
[badge-tip]: https://github.com/Mqxx/GitHub-Markdown/blob/main/blockquotes/badge/dark-theme/tip.svg 'Tip'

> ![badge-tip][badge-tip]<br>
> Tip
```
[badge-tip]: https://github.com/Mqxx/GitHub-Markdown/blob/main/blockquotes/badge/dark-theme/tip.svg 'Tip'

> ![badge-tip][badge-tip]<br>
> Tip

Use the following code to dynamically change the `Tip` icon based on user theme:
```
<picture>
 <source media="(prefers-color-scheme: dark)" srcset="https://github.com/Mqxx/GitHub-Markdown/blob/main/blockquotes/badge/dark-theme/tip.svg">
 <img alt="Shows an illustrated sun in light color mode and a moon with stars in dark color mode." src="https://github.com/Mqxx/GitHub-Markdown/blob/main/blockquotes/badge/light-theme/tip.svg">
</picture>
```

<br>

#### Issue Badge

```markdown
[badge-issue]: https://github.com/Mqxx/GitHub-Markdown/blob/main/blockquotes/badge/dark-theme/issue.svg 'Issue'

> ![badge-issue][badge-issue]<br>
> Issue
```
[badge-issue]: https://github.com/Mqxx/GitHub-Markdown/blob/main/blockquotes/badge/dark-theme/issue.svg 'Issue'

> ![badge-issue][badge-issue]<br>
> Issue

<br>

#### Success Badge

```markdown
[badge-success]: https://github.com/Mqxx/GitHub-Markdown/blob/main/blockquotes/badge/dark-theme/success.svg 'Success'

> ![badge-success][badge-success]<br>
> Success
```
[badge-success]: https://github.com/Mqxx/GitHub-Markdown/blob/main/blockquotes/badge/dark-theme/success.svg 'Success'

> ![badge-success][badge-success]<br>
> Success

<br>

#### Warning Badge

```markdown
[badge-warning]: https://github.com/Mqxx/GitHub-Markdown/blob/main/blockquotes/badge/dark-theme/warning.svg 'Warning'

> ![badge-warning][badge-warning]<br>
> Warning
```
[badge-warning]: https://github.com/Mqxx/GitHub-Markdown/blob/main/blockquotes/badge/dark-theme/warning.svg 'Warning'

> ![badge-warning][badge-warning]<br>
> Warning

<br>

#### Error Badge

```markdown
[badge-error]: https://github.com/Mqxx/GitHub-Markdown/blob/main/blockquotes/badge/dark-theme/error.svg 'Error'

> ![badge-error][badge-error]<br>
> Error
```
[badge-error]: https://github.com/Mqxx/GitHub-Markdown/blob/main/blockquotes/badge/dark-theme/error.svg 'Error'

> ![badge-error][badge-error]<br>
> Error

<br>

#### Danger Badge

```markdown
[badge-danger]: https://github.com/Mqxx/GitHub-Markdown/blob/main/blockquotes/badge/dark-theme/danger.svg 'Danger'

> ![badge-danger][badge-danger]<br>
> Danger
```
[badge-danger]: https://github.com/Mqxx/GitHub-Markdown/blob/main/blockquotes/badge/dark-theme/danger.svg 'Danger'

> ![badge-danger][badge-danger]<br>
> Danger

<br>

