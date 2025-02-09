<div align="center"></div>

```ascii
                    ____    _                     _   _             __  __                           _   _ 
                   |  _ \  (_)  _   _   __ _   __| | | |__         |  \/  |  _   _  _ __   __ _   __| | (_)
                   | |_) | | | | | | | / _` | / _` | | '_ \        | |\/| | | | | || '__| / _` | / _` | | |
                   |  _ <  | | | |_| || (_| || (_| | | | | |       | |  | | | |_| || |   | (_| || (_| | | |
                   |_| \_\ |_|  \__, | \__,_| \__,_| |_| |_|       |_|  |_|  \__,_||_|    \__,_| \__,_| |_|
                                |___/
```

````typescript
interface Developer {
  name: string;
  alias: string;
  age: number;
  location: {
    country: string;
    since: number;
  };
  education: string;
  languages: string[];
}

interface TechStack {
  activelyUsing: {
    frontend: string[];
    backend: string[];
    database: string[];
    tools: string[];
    design: string[];
  };
  learning: string[];
  wantToLearn: string[];
}

const aboutMe: Developer = {
  name: "Riyadh Muradi",
  alias: "Diar",
  age: 19,
  location: {
    country: "Finland",
    since: 2015
  },
  education: "Software Engineering Student",
  languages: ["Finnish", "Kurdish", "English"]
}

const techStack: TechStack = {
  activelyUsing: {
    frontend: [
      "Next.js",
      "React",
      "TypeScript",
      "Tailwind CSS",
      "Motion (Framer Motion)",
      "shadcn/ui"
    ],
    backend: [
      "Node.js",
      "Express"
    ],
    database: [
      "Supabase (PostgreSQL)",
      "MongoDB"
    ],
    tools: [
      "Git",
      "Docker",
      "Drizzle ORM"
    ],
    design: [
      "Adobe After Effects",
      "Adobe Premiere Pro",
      "Adobe Photoshop"
    ]
  },
  learning: [
    "PostgreSQL",
    "MongoDB",
    "Supabse",
    "Typescript",
    "Motion (Framer Motion",
    "SQL",
    "Zustand"
  ],
  wantToLearn: [
    "Java",
    "Kotlin",
    "Lua",
    "AWS"
  ]
}

{/* Currently focusing on: Coding and Full-stack development */}
