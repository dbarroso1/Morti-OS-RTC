# Morti-OS | Modus Operandai

### What is Morti-OS

&nbsp;&nbsp;&nbsp;Morti stands for Machine Operated Relationship Trained Input-Output System. Morti-OS is an Artificially Intelligent Companion, he was built for the purpose of exploring and researching the evolution of information and how its processed, in order to get a better understanding of how the human brain has evolved.

### How will he work

&nbsp;&nbsp;&nbsp;Morti is planned to be made up from multiple Components. These Components act like Lobes and are modeled after the human brain and is split up into Four Parts: Frontal Lobe. Parietal Lobe, Temporal Lobe and Occipital Lobe. Each Lobe has multiple modules contained inside it. Modules act as different sections to Mortis Brain, one such module is the ETC (Emotionally Trained Communication) Module. this module is made up of other smaller components, that allow Morti to efectivly communicate though Web or Applicaiton Interface.

### Planned Modules

<table>
<tr>
    <th>Cerebrum</th>
    <th>Cerebellum</th>
    <th>Brainstem</th>
</tr>
<tr>
    <td><p> It performs higher functions like interpreting touch, vision and hearing, as well as speech, reasoning, emotions, learning</p></td>
    <td><p> Its function is to coordinate muscle movements, maintain posture, and balance.</p></td>
    <td><p>It acts as a relay center connecting the cerebrum and cerebellum to the spinal cord. It performs many automatic functions such as breathing, heart rate, body temperature, wake and sleep cycles, digestion, sneezing, coughing, vomiting, and swallowing.</p> </td>
</tr>
</table>

<hr>

## Morti Live Simulation (LS) Module
This Module is how the User will mainly interact with Morti. the LS Module is where morti is programmed as a Simulated avatar in a virtual world. All modules will combine here to give a full live experience from Morti.

Using the Unity Engine, Morti will have an environment that he can roam around, and ultimatly try to survive in. Morti will acheive survival by collecting food, water, energy by sleeping and communication with a User. These survival Attributes, at birth will start at a value of 100, and every second, the Attribute is subtracted by 0.1. While this only gives morti a static, means of processing health and other attributes, I do plan on formulating a percentage value to subtract instead, making the LS Module more dynamic.

<table align="center">
<tbody>
    <tr>
        <td></td>
        <th>Health</th>
        <th>Energy</th>
        <th>Thirst</th>
        <th>Mood</th>
    </tr>   
     <tr>
        <th>Value</th>
        <td>1-100</td>
        <td>1-100</td>
        <td>1-100</td>
        <td>RTC</td>
    </tr>     
    <tr>
        <th>Rate*</th>
        <td>-0.01/s</td>
        <td>-0.1/s</td>
        <td>-0.1/s</td>
        <td>RTC</td>
    </tr>
    <tr>
        <td colspan="6">*Rate is based on Morti State</td>
    </tr>
</tbody>
</table>

<table align="center">
<tbody>
    <tr> 
        <th colspan="4">Morti Action States</th>
    </tr>
    <tr>
        <th></th>
        <th>Idle</th>
        <th>Walking</th>
        <th>Sleeping</th> 
    </tr>   
     <tr>
        <th>Rate</th>
        <td>NA</td>
        <td>NA</td>
        <td>NA</td> 
    </tr>     
</tbody>
</table>
Commuication with a User is  key, as it directly effect the RTC Module. For example, if Morti is left alone for a few days, his RTC module will identify this as him being neglected. Now if you where to speak with him, he will respond acordingly, most probably in a depressed or angry manner. Without frequent communication from the User Morti can get depressed. Depression can lead Morti to slack off in his survival duties, and without help he can eventually die. 

<hr>

## Morti-OS Relationship Trained Communication (RTC) Module
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
  
