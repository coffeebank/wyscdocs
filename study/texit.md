---
description: 'LaTeX renderer, Wolfram Alpha, calculations'
---

# TeXit

## Bot Info

{% embed url="https://top.gg/bot/510789298321096704" %}

## Basics

Prefix: `,`

* \#voice
* \#whiteboard
* \#bots
* Works in Wysc Library channels
* Works in Wysc Cafe channels
* Works in Wysc Lounge channels

## LaTeX

For special help and a tutorial on how to type equations, symbols, and other cool stuff in LaTeX, check out these fantastic resources:

{% page-ref page="../files/texit/latex-cheatsheet-for-texit.md" %}

{% page-ref page="../files/texit/the-great-big-list-of-latex-symbols.md" %}

## Commands

Italics are phrases you can replace with your own input.

<table>
  <thead>
    <tr>
      <th style="text-align:left">Command</th>
      <th style="text-align:left">Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">$ <em>\frac{1}{2} </em>$</td>
      <td style="text-align:left">LaTeX renderer (<a href="../files/texit/latex-cheatsheet-for-texit.md">see how to use</a>)</td>
    </tr>
    <tr>
      <td style="text-align:left">,wolf <em>4x^2</em>
      </td>
      <td style="text-align:left">Query WolframAlpha for <em>4x^2</em>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">,calc <em>1+1</em>
      </td>
      <td style="text-align:left">Calculator</td>
    </tr>
    <tr>
      <td style="text-align:left">,rotate</td>
      <td style="text-align:left">Rotates most recent image in the channel</td>
    </tr>
    <tr>
      <td style="text-align:left">,ti</td>
      <td style="text-align:left">Shows your timezone</td>
    </tr>
    <tr>
      <td style="text-align:left">,ti --set <em>7</em>
      </td>
      <td style="text-align:left">
        <p>Set your timezone by <em>current hour</em>
        </p>
        <p><em><b>Note: If the time is 7:35pm, only put 7</b></em>
        </p>
      </td>
    </tr>
  </tbody>
</table>

{% tabs %}
{% tab title="Notifications" %}
#### ,notifyme

Notifyme sends you a direct message whenever messages matching your criteria are detected.

`,notifyme text --condition`

| Condition | Description |
| :--- | :--- |
| --remove | Displays a menu where you can select a check to remove. |
| --mentions | Requires the message to mention this user. |
| --contains | Requires message to contain this string. |
| --here | Requires message to be from this server. |
| --from | Requires message to be from the specified user. |
| --notbot | Requires the message not have been sent by a bot. |
{% endtab %}
{% endtabs %}

## Full Commands

Type `,help` in \#bots



