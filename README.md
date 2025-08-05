
```typescript
interface Developer {
  name: string;
  role: string;
  location: string;
  currentlyWorking: string[];
  learningNext: string[];
  funFact: string;
  motto: string;
}

const harsh: Developer = {
  name: "Harsh Kumar",
  role: "Frontend Engineer (React & Next.js)",
  location: "Delhi, India 🇮🇳",
  currentlyWorking: [
    "Building full-stack features at early-stage startups",
    "Turning Figma designs into responsive UIs",
    "Writing UI feedback & code reviews (300+ on Frontend Mentor)",
    "Using AI tools (ChatGPT, Claude, Amazon Q) to ship faster"
  ],
  learningNext: ["System Design", "TypeScript Patterns", "DevOps Basics"],
  funFact: "I once built 30+ webpages in 30 days just for fun.",
  motto: "Still learning. Still building. Always curious."
};
```
