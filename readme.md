# Morti-OS Relationship Trained Communication (RTC) Module
The RTC Module is used by Morti as its main method of communication with the User. The goal of the RTC Module is to process User inputs, and define the context of said input, while calculating an emotional value (1-10) to the expression given.

```
[Example]

You: Hello Morti, today was a bad day

Morti: why was it a bad day?

You: my car broke down in the highway!

Morti: well that sounds frustrating 
// Morti Understands that a personal Item was damaged
````

## Emotional quantification
Morti is planned to have a vast array of emotional responses. Although the amount of emotional responses are limited to Six Primary Emotions, Morti can calculate multiple emotions to get acheive Secondary Emotional responses. (See Image Below)
Each word in the Input Phrase is seperated from the whole, given a corresponding Emotional Weight, and is then its averaged out to find the phrases Emotional Score.

<table>
<tr>
<th colspan="1">Complete Phrase</th>
<td colspan="5">Hey, I think you suck.</td>
</tr>
<tr>
<th>Phrases</th>
<td>Hey, </td>
<td>I</td>
<td>think</td>
<td>you</td>
<td>suck</td>
</tr>
<tr>
<th>Parts of Speech</th>
<td>interjection</td>
<td>Noun</td>
<td>Verb</td>
<td>Noun</td>
<td>Verb</td>
</tr>
<tr>
<th>Wieght</th>
<td>0</td>
<td>0</td>
<td>0</td>
<td>0</td>
<td>
<strong>1</strong>
</td>
</tr>
</table>
