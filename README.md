# CodeProject

CodeProject (https://www.codeproject.com/) is a long-running online community for software developers, providing articles, tutorials, code samples, tips, and a question-and-answer forum across a broad range of programming topics. Founded in 1999, it hosts hundreds of thousands of developer-contributed articles covering languages, frameworks, algorithms, and tools, with content rated and moderated by the community. CodeProject also operates CodeProject.AI (https://codeproject.ai/), a self-hosted AI server that exposes AI capabilities such as object detection, face recognition, and scene analysis through a local HTTP REST API.

**URL:** [https://www.codeproject.com/](https://www.codeproject.com/)

## APIs

### CodeProject REST API

CodeProject provides a REST API available at [https://api.codeproject.com](https://api.codeproject.com). The initial release (V1 Beta) offers read access to the following resource types:

- **Articles** — Retrieve the latest articles, technical blogs, and tips & tricks (rating >= 3.0), ordered by modified date.
- **Forum Messages** — Access the latest messages for a forum or message thread.
- **Questions** — Retrieve the latest new, active, or unanswered questions from the Q&A section.
- **User (My)** — Access authenticated user data including answers, articles, blog posts, bookmarks, notifications, profile, reputation, and tips.

**Base URL:** `https://api.codeproject.com`

**Authentication:** OAuth2 Bearer Tokens. Supported flows:
- Client Credentials Grant — for applications accessing public content without user context.
- Authorization Code Grant — for accessing user-owned resources.
- Implicit Grant — an alternative user-delegated flow.

Tokens must be sent in the `Authorization` header of each HTTPS request.

**Documentation:** [https://api.codeproject.com/Help](https://api.codeproject.com/Help)

**Samples:** [https://api.codeproject.com/Samples](https://api.codeproject.com/Samples)

### CodeProject.AI Server API

CodeProject.AI Server (https://codeproject.ai/) is a self-contained, self-hosted service that exposes AI capabilities via a local HTTP REST API. It is designed to be bundled with developer applications to add AI features without cloud dependencies.

Key endpoint categories include:
- `/v1/vision/detect/scene` — Scene detection
- `/v1/vision/detection` — Object detection
- `/v1/vision/face` — Face detection and recognition
- `/v1/server/modules/update` — Module management

**GitHub:** [https://github.com/codeproject/CodeProject.AI-Server](https://github.com/codeproject/CodeProject.AI-Server)

**Documentation:** [https://codeproject.github.io/codeproject.ai/](https://codeproject.github.io/codeproject.ai/)
