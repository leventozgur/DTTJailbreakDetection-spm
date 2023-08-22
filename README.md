# DTTJailbreakDetection-spm

This is a version of the DTTJailbreakDetection library that has been adapted to be compatible with Swift Package Manager (SPM). The original DTTJailbreakDetection repository can be found at: [https://github.com/thii/DTTJailbreakDetection](https://github.com/thii/DTTJailbreakDetection)

## About DTTJailbreakDetection

DTTJailbreakDetection is a library that provides the capability to detect whether an iOS device is jailbroken or not.

## Installation

You can integrate DTTJailbreakDetection into your project using Swift Package Manager.

### Swift Package Manager

1. Open your Xcode project.
2. Select your project in the Project Navigator.
3. Navigate to the Swift Packages tab.
4. Click the "+" button to add a package.
5. Enter the URL of this repository: `https://github.com/leventozgur/DTTJailbreakDetection-spm`
6. Choose the version rule according to your preferences.
7. Click Next, then Finish.

## Usage

After adding DTTJailbreakDetection as a Swift Package, you can import and use its functionality in your code. Here's a simple example:

```swift
import DTTJailbreakDetection_spm

class ViewController: UIViewController {
    override func viewDidLoad() {
        super.viewDidLoad()

        if DTTJailbreakDetection.isJailbroken() {
            print("Device is jailbroken.")
        } else {
            print("Device is not jailbroken.")
        }
    }
}
