# Semantic HTML

## Semantic means “relating to meaning”

Semantics are elements that describe its content through its meaning.

### Advantages of semantic HTML

it helps in making code readable and easy to maintain
it also helps in web accessibility, screen readers tend to be able to access a website with semantic HTML faster
it also helps with search engine optimization.

### Examples of semantics and how and where they are used;

- form
- table
- title
- header
- video
- audio
- strong
- aside
- figcaption
- footer
- img
- figure
- section
- article
- nav

## img

     This is a non-closing semantic tag used for images

`<img src="image URL" alt="describes the picture in preferably short words">`

## form

    This is used to create forms for users to input their data or information.

Example:

```html
<form>
  <label for="gender" id="gender" name="gender">Name</label>
  <input type="text" />
</form>
```

## Table

    This is used to construct a table to input data in tabular form, it includes `<th>` which is table header,`<tr>` which is table row, and table data/cell which is `<td>`.

Example

```html
<table>
  <tr>
    <th>Name</th>
    <th>Gender</th>
    <th>Age</th>
  </tr>

  <tr>
    <td>Abimbola</td>
    <td>Female</td>
    <td>6</td>
  </tr>
</table>
```

## aside

    This is a semantic element that holds information that is not important to the title of the page but still has some relevance, it usually uses for quotes,short-text, historical content, advertisement.

## nav

    Navigation tag usually holds up links, content that stays on the head of a page to navigate down the page.

## footer

    As the name implies this holds information of the down part of the page such as copyright, references, site information, contacts.

## header

    This is a semantic element that holds the upper part of site information such as the title, main headings, images.

## strong

    This is an element that makes a particular word or statement bold.

## abbr

    This tag is usually used to abbreviate longer words, meaning can be written inside it to give details when the cursor moves around it.

## audio

    This is a tag that is used to create audio on a page, it requires the control and the source URL and the type of media it is using such as mp3 or mp4.

## video

    it is used to create a video on a page, like the audio element it requires the control and the source link of the video.

### Examples of non-semantics and how and where they are used;

- div
- span

## div

    the div tag is a block container, and it serves as a container element for all block contents.

## span

    span is an inline container, it serves as a container element for all inline contents. Non-semantic are also important but should be used to the barest minimum and when content has no relative semantic tag.
