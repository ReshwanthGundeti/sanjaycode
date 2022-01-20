# sanjaycode
import UIKit

var greeting = "Hello, playground"

print("Hii",10,12.25)
var name = "ajay"
var grade = "B"
print("hello, \(name)! you got \(grade) in ios course.")
var age = 23
print("your age is \(age) and when it is trippled your age is \(age * 3) ")
print("""
      hiiii
      you
      """)
print("welcome to swift programming")
print("fall 2021")
print("*************")
print("welcome to swift programming" , terminator : "-")
print("fall 2021")
print("hello, \(name)" , terminator: "@@")
print("you got \(grade) percentage in ios")

print("The list of numbers are ")
print(1,2,3,4,5,6)
print("The new pattern is" , terminator: "{")
print(1,2,3,4,5,6, separator: "*")

var laptop = ("apple,windows")
laptop = ("linux")
print(laptop)

var age1 : Int = 32
age1 = age1 * 2
print(age1)

var course1 = "pm"
var course2 = "am"
print(course2, terminator:"-")
print(course1,course2, separator: "&")


--------------------------------------------------------------------
import UIKit

class ViewController: UIViewController {

    @IBOutlet weak var NameOutlet: UITextField!
    
    @IBOutlet weak var gradeoutlet: UITextField!
    
    @IBOutlet weak var Displaylable: UILabel!
    
    @IBOutlet weak var outputlable: UILabel!
    
    override func viewDidLoad() {
        super.viewDidLoad()
        // Do any additional setup after loading the view.
    }


    @IBAction func buttonclicked(_ sender: UIButton) {
        //read the data from the text box and store it and change the display format, hellow, name!
        var name = NameOutlet.text!
        var grade = gradeoutlet.text!
        Displaylable.text = "Hello, \(name)! your grsde is \(grade)."

    }
}

