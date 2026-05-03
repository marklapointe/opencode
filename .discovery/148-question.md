148-question.md

Directory: src/question/

Overview: Question subsystem for interactive prompts, including a Question.Info model, tooling for asking questions, and a bus-based reply mechanism.

- index.ts
  - Exports: Question.Service, Question.Info, Question.Tool, Question.Request, Event (Asked, Replied, Rejected)
  - Role: Orchestrates asking questions to the user and handling replies/new requests
- schema.ts
  - Exports: Question-related types and STUBs used in the Question flow
- The module demonstrates a clear pattern of exporting * as Question from "." to provide a namespace

End of 148-question.md
