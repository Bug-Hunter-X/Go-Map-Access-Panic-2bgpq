# Go Map Access Panic

This repository demonstrates a common error in Go: panics caused by accessing non-existent keys in maps.  Maps in Go do not return default values upon access of a missing key; instead, they panic. This can lead to unexpected application crashes.

## Bug Description
The `bug.go` file shows how attempting to access a map with a missing key results in a runtime panic.

## Solution
The `bugSolution.go` demonstrates the safe way to handle map access by checking for the existence of a key before accessing its value.

## How to Run
1. Clone the repository.
2. Navigate to the repository's directory.
3. Run `go run bug.go` to see the panic.
4. Run `go run bugSolution.go` to see the safe solution in action. 