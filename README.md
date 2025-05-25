# CivIQ AI 🏛️🤖

**CivIQ AI** is an intelligent civic management platform combining Next.js, Flutter, and Google Cloud AI to revolutionize facility bookings and community issue resolution.


## Features ✨

### For Citizens
- **Conversational AI**: Natural language processing for bookings/reports
- **Cross-Platform Access**: Web (Next.js) and mobile (Flutter) interfaces
- **Smart Tracking**: Real-time status updates for requests

### For Administrators
- **AI-Powered Dashboard**:  
  🔴 Urgent (Vertex AI sentiment analysis)  
  📝 Auto-summarized complaints (Gemini)  
  📊 Aparavi-driven data insights
- **Multi-Platform Management**: Approve/reject requests from any device

## Tech Stack 🛠️

### Core Architecture
| Layer             | Technologies                                                                 |
|-------------------|-----------------------------------------------------------------------------|
| **Frontend**      | Next.js 14 (App Router), React 18, ShadCN UI, Tailwind CSS                  |
| **Mobile**        | Flutter 3.x (iOS/Android)                                                  |
| **AI Engine**     | Google Genkit, Gemini Pro 1.5, Vertex AI NLP models                        |
| **Data Pipeline** | Aparavi for intelligent document processing                                |
| **State**         | React Context API + Flutter BLoC                                           |

### Key Integrations
```mermaid
graph LR
A[Next.js Web] --> B[Genkit]
C[Flutter App] --> B
B --> D{GCloud AI}
D --> E[Gemini]
D --> F[Vertex AI]
B --> G[Aparavi]
