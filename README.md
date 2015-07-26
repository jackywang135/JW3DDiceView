# JW3DDiceView

Allows you to easily implement a 3D Dice rolling view into your UI with simple APIs. 

![Demo](https://cloud.githubusercontent.com/assets/8235878/8893213/9b991162-33ba-11e5-8dcb-75d645bb5ee6.gif)

![iPad Demo](https://cloud.githubusercontent.com/assets/8235878/8893549/a887f4f4-33c6-11e5-82f8-eed375c2e0ad.gif)

#Usage

You may 
* Add Dice 
```
  diceView.addDice()
```
* Delete Dice
```
  diceView.deleteDice()
```
* Roll Dice
```
  diceView.roll()
```
* Get Total 
```
 diceView.total
```

And be notified when 
* Did start & end of rolling 
* Did reach max & go under dice capacity 

#Customization

You may customize these properties

* Dice Size 
* Activate shake in response to Device Motion 
* Sound
* Background Image

#Installation 

1. Download or Clone the project

2. Drag the JW3DDiceView.swift file into your project

3. Add the images in folder "RequiredImages" into your image assets

4. Add the "ShakeAndRollDice.mp3" file into your project if you'd like to enable sound.

#App Store

Used in App [Dice Field 3D](https://itunes.apple.com/us/app/dice-field-3d/id946490633?mt=8) in the App Store. [Repository](https://github.com/jackywang135/Dice-Field-3D)
