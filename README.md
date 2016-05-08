# SwiftyOAuth

```swift
let github: Provider = .GitHub(
    clientID: "**********",
    clientSecret: "**********",
    redirectURL: "myapp://callback"
)

github.authorize { result in
    switch result {
    case .Success(let credentials):
        print(credentials.token)
    case .Failure(let error):
        print(error)
    }
}
```

## Usage

### Providers

- GitHub
- Twitter
- Facebook
- Weibo
- Instagram
- Dribbble

## Demo

## Installation

#### Carthage

#### CocoaPods

## License
