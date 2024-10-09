# Ideas for refactoring main.go

## Dave W 9th Oct 2024

1. move types to seperate file (and import?)
2. move gmae datat to seperate file (and import?)
3. move switch from L599 to seperte function
   - this is a big move to do in one go, as associated vars need to be in-scope. Try moving case-by-case...
