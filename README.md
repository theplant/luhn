# Luhn Algorithm

Generating check number & validating Luhn numbers in GO

# Usage

```go
import "github.com/theplant/luhn"

func main() {
	// Checking if a string is a valid luhn
	luhn.Valid(1111) //= false
	luhn.Valid(79927398713) //= true

  luhn.CalculateLuhn(7992739871) //= 3
}
```
