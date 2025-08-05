
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
  learningNext: [
    "React Native",
    "Full-Stack Development",
    "DSA (C/C++)"
  ],
  funFact: "I once built 30+ UIs in 30 days just for fun.",
  motto: "Still learning. Still building. Always curious."
};
```
