# Uncaught ReferenceError: arr4 is not defined

This repository demonstrates a common runtime error in TypeScript that arises from referencing a variable before it has been initialized.  The type system catches many errors, but this one slips through because the error occurs *during* execution, not during compilation. The solution highlights how to prevent this.