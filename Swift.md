# Swift Basics

#### 1. Swift Open Source Projs: dkhamsing/open-source-ios-apps
#### 2. Fill Own Image: 'Aspect Fill' BETTER than 'Scale To Fill'/ 'Aspect Fit': same as original
#### 3. Duplicate: Press on 'option' key and drag
#### 4. Main.storyboard --> Top Right Corner --> Adjust Editor Options --> Assistant
#### 5. Click on 'control' button --> Hold click on specific element --> Drag it into before 'override' line
#### &emsp; @IBOutlet weak var diceImageViewOne: UIImageView!
#### 6. Change Elements'names: Refactor
#### 7. When Loaded Change Image:  diceImageViewOne.image = #imageLiteral(resourceName: "DiceSix");
#### 8. 'Roll" Buttion Connection Type: Action --> Drag below the func 'viewDidLoad' --> Event: Touch Up Inside --> Type: UIButton
#### &emsp; @IBAction func rollButtonPressed(_ sender: Any) { }
#### 9. Single Line Comment: //    Multi Lines Comment: /* 
#### 10. String Interpolation(插值 内插): Print("Hello \(2+3) World") --> Hello 5 World
#### 11. Storing Data using Variables and Arrays
#### &emsp; Array: []: Same space between the '=' assignment
#### &emsp; var --- variable; let --- constant
#### 12. Double: doubles the precision of float
#### 13. Range Operator 'in': in: lower ... upper(inclusive)/ lower ..< upper(exclusive)
#### 14. Randomise Array: array.randomElement() / array.shuffle()
#### &emsp;  func exercise() {
    
#### &emsp; &emsp;     let alphabet = ["a","b","c","d","e","f","g","h","i","j","k","l","m","n","o","p","q","r","s","t","u","v","w","x","y","z"]
    
#### &emsp; &emsp;    //The number of letters in alphabet equals 26
    
#### &emsp; &emsp;     let password = alphabet.shuffled().prefix(6).joined()
    
#### &emsp; &emsp;     print(password)
    
#### &emsp; &emsp; }


