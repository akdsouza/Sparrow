![](/Img/sparrow.jpg)

## Description
The library for simplify iOS programming in Swift. Сode written by sticking paradigms Steve McConnell in his book "Сode Сomplete". 

I think that programmist at first think about the idea, and only then on the implementation. In library collected routine actions, which every programmist must realesed and realesed. Programmis shoud do product, but implementation simply action as "Inn-App" or "How play sound".

Now added Game Center, In-App Purchase, AudioPlayer and other.

## Installation
Drop in the Sparrow folder to your Xcode project. Add some lines of code and it work! 

![](/Img/installation.jpg)

## In-App Purchase

    let purchase = Product(productID: "insert_in-app_id")
    purchase.funcWithPurchased = {
        print("bought")
    }
    purchase.buy()

## Game Center

    let gameCenter = GameCenterManager(rootViewController: self)

    gameCenter.authorizateInGameCenter()
    gameCenter.saveHighscore(30, toLiderboard: "insert_liderboardID")
    gameCenter.showLeaderboard("insert_liderboardID")

# Achivment

    let achivment = Achivment(ID: "insert_achivment_id")
    achivment.setPercentCompleteTo(80)
    achivment.sendAchivmentToServer()

or else

    sendAchivmentToServer([achivment_1, achivment_2])

# Banner GC

    showNotificationBannerWithTitle("Sparrow", messege: "Simplify iOS programming")

![](/Img/banner GameCenter.jpg)

## Sound

    var sparrowSound = AudioPlayer(fileName: "sparrow.mp3")
    sparrowSound.play()

or else

    var audio = AudioPlayer()
    audio.playSound("sparrow.mp3")
    audio.playSound("colibri.wav")

## Sparrow UI
    
    Blur, animation and Views for your project. Adaptive and with clean code.

![](/Img/sparrow ui.jpg) 

## Detailed Report

During the execution of each complex action you will receive a detailed report to the console It is necessary to control: for example, you make a mistake in entering the ID of the internal purchases.

![](/Img/log.jpg)

## License and Contact
Sparrow is released under the MIT license. See LICENSE.md for details.

Contact:
 
    www.ivanorobei.by
    ivanvorobei@icloud.com
    www.facebook.com/ivanvorobeisparrow
    
![](/Img/feature.jpg)