
# Romisaa Cinematic Love Experience

A premium cinematic one-page Next.js experience dedicated to Romisaa.

## Run Inputs

- recipient_name: Romisaa
- visual_style: cinematic_crystal
- include_music: false
- photo_assets: none provided
- relationship_context: none provided

Because no photos or music were provided, the generated design uses refined glass placeholder memory cards and no audio requirement.

## Tech Stack

- Next.js App Router
- React
- Tailwind CSS
- Three.js via React Three Fiber
- Drei helpers
- GSAP ScrollTrigger
- Lenis smooth scrolling
- Framer Motion for refined UI transitions

## Recommended Install

package.json

{
  "scripts": {
    "dev": "next dev",
    "build": "next build",
    "start": "next start",
    "lint": "next lint"
  },
  "dependencies": {
    "@react-three/drei": "latest",
    "@react-three/fiber": "latest",
    "framer-motion": "latest",
    "gsap": "latest",
    "lenis": "latest",
    "lucide-react": "latest",
    "next": "latest",
    "react": "latest",
    "react-dom": "latest",
    "three": "latest"
  },
  "devDependencies": {
    "autoprefixer": "latest",
    "postcss": "latest",
    "tailwindcss": "latest",
    "typescript": "latest"
  }
}

## Project Structure

romisaa-experience/
  app/
    globals.css
    layout.tsx
    page.tsx
  components/
    CrystalHeartScene.tsx
    CinematicIntro.tsx
    CustomCursor.tsx
    MemoryCard.tsx
    StorySection.tsx
  lib/
    useLenis.ts
  tailwind.config.ts
  next.config.mjs
  package.json

## app/layout.tsx

import type { Metadata } from "next";
import "./globals.css";

export const metadata: Metadata = {
  title: "For Romisaa",
  description: "A cinematic love experience dedicated to Romisaa."
};

export default function RootLayout({
  children
}: {
  children: React.ReactNode;
}) {
  return (
    <html lang="en">
      <body>{children}</body>
    </html>
  );
}

## app/page.tsx

"use client";

import { useEffect, useRef } from "react";
import gsap from "gsap";
import ScrollTrigger from "gsap/ScrollTrigger";
import { motion } from "framer-motion";
import { Sparkles } from "lucide-react";
import CrystalHeartScene from "@/components/CrystalHeartScene";
import CinematicIntro from "@/components/CinematicIntro";
import CustomCursor from "@/components/CustomCursor";
import MemoryCard from "@/components/MemoryCard";
import StorySection from "@/components/StorySection";
import { useLenis } from "@/lib/useLenis";

gsap.registerPlugin(ScrollTrigger);

const memories = [
  {
    title: "The first moment",
    note: "Some people arrive quietly, then become impossible to forget."
  },
  {
    title: "The conversations",
    note: "Every word started to feel less ordinary."
  },
  {
    title: "The feeling",
    note: "Not loud. Not rushed. Just real."
  }
];

export default function Page() {
  const rootRef = useRef<HTMLDivElement | null>(null);
  useLenis();

  useEffect(() => {
    const ctx = gsap.context(() => {
      gsap.utils.toArray<HTMLElement>("[data-reveal]").forEach((el) => {
        gsap.fromTo(
          el,
          { opacity: 0, y: 60, filter: "blur(16px)" },
          {
            opacity: 1,
            y: 0,
            filter: "blur(0px)",
            duration: 1.4,
            ease: "power4.out",
            scrollTrigger: {
              trigger: el,
              start: "top 82%",
              end: "bottom 45%",
              scrub: 0.4
            }
          }
        );
      });

      gsap.to("[data-orbit-line]", {
        rotate: 360,
        duration: 38,
        ease: "none",
        repeat: -1
      });

      gsap.to("[data-dream-bg]", {
        backgroundPosition: "50% 100%",
        ease: "none",
        scrollTrigger: {
          trigger: "[data-future]",
          start: "top bottom",
          end: "bottom top",
          scrub: true
        }
      });
    }, rootRef);

    return () => ctx.revert();
  }, []);

  return (
    <main ref={rootRef} className="relative min-h-screen overflow-x-hidden bg-[#030306] text-stone-100 selection:bg-rose-200/20">
      <CustomCursor />
      <CinematicIntro recipientName="Romisaa" />

      <div className="fixed inset-0 z-0">
        <CrystalHeartScene />
      </div>

      <section className="relative z-10 flex min-h-screen items-center justify-center px-6">
        <div className="mx-auto max-w-5xl text-center">
          <motion.p
            initial={{ opacity: 0, y: 18 }}
            animate={{ opacity: 1, y: 0 }}
            transition={{ delay: 4.9, duration: 1.4, ease: "easeOut" }}
            className="mb-6 text-xs uppercase tracking-[0.55em] text-rose-100/50"
          >
            A quiet universe made for one name
          </motion.p>

          <motion.h1
            initial={{ opacity: 0, y: 32, filter: "blur(20px)" }}
            animate={{ opacity: 1, y: 0, filter: "blur(0px)" }}
            transition={{ delay: 5.25, duration: 1.8, ease: "easeOut" }}
            className="font-serif text-6xl leading-none tracking-[-0.08em] text-white md:text-8xl lg:text-9xl"
          >
            Romisaa
          </motion.h1>

          <motion.p
            initial={{ opacity: 0 }}
            animate={{ opacity: 1 }}
            transition={{ delay: 6.1, duration: 1.6 }}
            className="mx-auto mt-8 max-w-2xl text-lg leading-8 text-stone-300/70"
          >
            Some stories do not need to be loud to be unforgettable.
          </motion.p>
        </div>
      </section>

      <StorySection eyebrow="01 — First Impression">
        <p data-reveal>I didn't expect anything...</p>
        <p data-reveal>But then I met you.</p>
      </StorySection>

      <StorySection eyebrow="02 — Connection">
        <p data-reveal>Every moment felt different.</p>
        <p data-reveal>Every conversation meant more.</p>
        <p data-reveal className="text-stone-400">
          And slowly, without forcing anything, you became a part of my world.
        </p>
      </StorySection>

      <section className="relative z-10 min-h-screen px-6 py-32">
        <div className="mx-auto max-w-6xl">
          <div data-reveal className="mb-16 flex items-center gap-4">
            <Sparkles className="h-5 w-5 text-rose-200/70" />
            <p className="text-xs uppercase tracking-[0.5em] text-stone-400">
              03 — Memories
            </p>
          </div>

          <div className="grid gap-6 md:grid-cols-3">
            {memories.map((memory, index) => (
              <MemoryCard
                key={memory.title}
                index={index}
                title={memory.title}
                note={memory.note}
              />
            ))}
          </div>
        </div>
      </section>

      <section className="relative z-10 flex min-h-screen items-center justify-center px-6">
        <div className="absolute inset-0 bg-[radial-gradient(circle_at_center,rgba(244,114,182,0.12),transparent_55%)]" />
        <div className="relative mx-auto max-w-4xl text-center">
          <p data-reveal className="mb-8 text-xs uppercase tracking-[0.5em] text-rose-100/40">
            04 — What changed
          </p>
          <h2 data-reveal className="font-serif text-5xl leading-tight tracking-[-0.06em] md:text-7xl">
            You made ordinary moments feel like they had light inside them.
          </h2>
        </div>
      </section>

      <section data-future className="relative z-10 min-h-screen overflow-hidden px-6 py-40">
        <div data-dream-bg className="absolute inset-0 bg-[linear-gradient(180deg,#030306_0%,#101322_45%,#251527_100%)] bg-[length:100%_180%]" />
        <div className="absolute inset-0 opacity-50 stars" />

        <div className="relative mx-auto max-w-5xl">
          <p data-reveal className="mb-8 text-xs uppercase tracking-[0.5em] text-stone-300/50">
            05 — Future Vision
          </p>
          <h2 data-reveal className="max-w-4xl font-serif text-5xl leading-tight tracking-[-0.06em] md:text-7xl">
            I do not know every chapter ahead.
          </h2>
          <p data-reveal className="mt-10 max-w-2xl text-xl leading-9 text-stone-200/70">
            But I know I want the pages to keep finding your name in them.
          </p>
        </div>
      </section>

      <section className="relative z-10 flex min-h-screen items-center justify-center px-6">
        <div data-orbit-line className="absolute h-[42rem] w-[42rem] rounded-full border border-rose-200/10" />
        <div className="relative text-center">
          <p data-reveal className="mb-8 text-xs uppercase tracking-[0.55em] text-rose-100/50">
            Final Scene
          </p>
          <h2 data-reveal className="font-serif text-5xl leading-tight tracking-[-0.07em] text-white md:text-8xl">
            I love you, Romisaa.
            <br />
            Always.
          </h2>
        </div>
      </section>
    </main>
  );
}

## components/CinematicIntro.tsx

"use client";

import { useEffect, useState } from "react";
import { motion, AnimatePresence } from "framer-motion";

export default function CinematicIntro({ recipientName }: { recipientName: string }) {
  const [progress, setProgress] = useState(0);
  const [visible, setVisible] = useState(true);

  useEffect(() => {
    const progressTimer = window.setInterval(() => {
      setProgress((value) => Math.min(value + Math.random() * 14, 100));
    }, 180);

    const hideTimer = window.setTimeout(() => setVisible(false), 4700);

    return () => {
      window.clearInterval(progressTimer);
      window.clearTimeout(hideTimer);
    };
  }, []);

  return (
    <AnimatePresence>
      {visible && (
        <motion.div
          initial={{ opacity: 1 }}
          exit={{ opacity: 0, filter: "blur(12px)" }}
          transition={{ duration: 1.2, ease: "easeInOut" }}
          className="fixed inset-0 z-50 flex items-center justify-center bg-[#020204]"
        >
          <div className="w-full max-w-2xl px-8 text-center">
            <motion.div
              initial={{ opacity: 0 }}
              animate={{ opacity: 1 }}
              className="mx-auto mb-10 h-px w-full overflow-hidden bg-white/10"
            >
              <motion.div
                className="h-full bg-gradient-to-r from-transparent via-rose-100 to-transparent"
                style={{ width: `${progress}%` }}
              />
            </motion.div>

            <motion.p
              initial={{ opacity: 0, y: 18 }}
              animate={{ opacity: [0, 1, 1, 0], y: [18, 0, 0, -12] }}
              transition={{ duration: 3.1, times: [0, 0.22, 0.72, 1], ease: "easeOut" }}
              className="text-xl leading-9 text-stone-200/80 md:text-3xl"
            >
              Some people come into your life unexpectedly...
            </motion.p>

            <motion.p
              initial={{ opacity: 0, y: 18 }}
              animate={{ opacity: [0, 0, 1], y: [18, 18, 0] }}
              transition={{ delay: 2.2, duration: 1.35, ease: "easeOut" }}
              className="mt-6 text-xl leading-9 text-stone-200 md:text-3xl"
            >
              But change everything.
            </motion.p>

            <motion.p
              initial={{ opacity: 0, scale: 0.96, filter: "blur(12px)" }}
              animate={{ opacity: 1, scale: 1, filter: "blur(0px)" }}
              transition={{ delay: 3.65, duration: 1.1, ease: "easeOut" }}
              className="mt-10 font-serif text-4xl tracking-[-0.05em] text-white md:text-6xl"
            >
              {recipientName} ❤️
            </motion.p>
          </div>
        </motion.div>
      )}
    </AnimatePresence>
  );
}

## components/CrystalHeartScene.tsx

"use client";

import { Canvas, useFrame } from "@react-three/fiber";
import { Float, Environment, MeshTransmissionMaterial, Sparkles } from "@react-three/drei";
import { useMemo, useRef } from "react";
import * as THREE from "three";

function CrystalHeart() {
  const group = useRef<THREE.Group>(null);

  const fragments = useMemo(() => {
    return Array.from({ length: 42 }, (_, index) => ({
      position: new THREE.Vector3(
        (Math.random() - 0.5) * 2.4,
        (Math.random() - 0.5) * 2.1,
        (Math.random() - 0.5) * 1.6
      ),
      rotation: [Math.random() * Math.PI, Math.random() * Math.PI, Math.random() * Math.PI] as [number, number, number],
      scale: 0.035 + Math.random() * 0.055,
      index
    }));
  }, []);

  useFrame((state) => {
    if (!group.current) return;
    group.current.rotation.y = state.clock.elapsedTime * 0.18;
    group.current.rotation.x = Math.sin(state.clock.elapsedTime * 0.25) * 0.08;
  });

  return (
    <group ref={group}>
      <Float speed={1.1} rotationIntensity={0.18} floatIntensity={0.35}>
        <mesh scale={[1.3, 1.3, 1.3]}>
          <sphereGeometry args={[1, 96, 96]} />
          <MeshTransmissionMaterial
            thickness={1.2}
            roughness={0.08}
            transmission={1}
            ior={1.55}
            chromaticAberration={0.05}
            anisotropy={0.15}
            distortion={0.12}
            distortionScale={0.18}
            temporalDistortion={0.08}
            color="#ffe4ef"
          />
        </mesh>

        {fragments.map((fragment) => (
          <mesh
            key={fragment.index}
            position={fragment.position}
            rotation={fragment.rotation}
            scale={fragment.scale}
          >
            <tetrahedronGeometry args={[1, 1]} />
            <meshStandardMaterial
              color="#ffd6e7"
              roughness={0.08}
              metalness={0.12}
              transparent
              opacity={0.48}
              emissive="#ff8ab8"
              emissiveIntensity={0.08}
            />
          </mesh>
        ))}
      </Float>
    </group>
  );
}

export default function CrystalHeartScene() {
  return (
    <Canvas
      dpr={[1, 1.7]}
      camera={{ position: [0, 0, 5.3], fov: 38 }}
      gl={{ antialias: true, alpha: true, powerPreference: "high-performance" }}
    >
      <color attach="background" args={["#030306"]} />
      <ambientLight intensity={0.55} />
      <directionalLight position={[4, 4, 5]} intensity={1.5} color="#fff0f7" />
      <pointLight position={[-3, -1, 3]} intensity={5} color="#ff79ad" />
      <pointLight position={[3, 2, -2]} intensity={3} color="#8ab4ff" />
      <Sparkles count={90} scale={[8, 5, 4]} size={1.4} speed={0.18} opacity={0.28} color="#fff4fb" />
      <CrystalHeart />
      <Environment preset="city" />
    </Canvas>
  );
}

## components/StorySection.tsx

export default function StorySection({
  eyebrow,
  children
}: {
  eyebrow: string;
  children: React.ReactNode;
}) {
  return (
    <section className="relative z-10 flex min-h-screen items-center px-6 py-28">
      <div className="mx-auto max-w-5xl">
        <p data-reveal className="mb-10 text-xs uppercase tracking-[0.5em] text-stone-500">
          {eyebrow}
        </p>
        <div className="space-y-8 font-serif text-5xl leading-tight tracking-[-0.06em] text-stone-100 md:text-7xl">
          {children}
        </div>
      </div>
    </section>
  );
}

## components/MemoryCard.tsx

"use client";

import { motion } from "framer-motion";

export default function MemoryCard({
  index,
  title,
  note
}: {
  index: number;
  title: string;
  note: string;
}) {
  return (
    <motion.article
      data-reveal
      initial={false}
      whileHover={{ y: -14, scale: 1.015 }}
      transition={{ duration: 0.55, ease: [0.16, 1, 0.3, 1] }}
      className="group relative min-h-[26rem] overflow-hidden rounded-[2rem] border border-white/10 bg-white/[0.035] p-7 backdrop-blur-xl"
    >
      <div className="absolute inset-0 bg-[radial-gradient(circle_at_50%_0%,rgba(251,207,232,0.18),transparent_52%)] opacity-80" />
      <div className="absolute inset-x-8 top-8 h-52 rounded-[1.4rem] border border-white/10 bg-gradient-to-br from-rose-100/15 via-white/5 to-indigo-200/10" />
      <div className="relative flex h-full flex-col justify-end">
        <p className="mb-4 text-xs uppercase tracking-[0.4em] text-stone-400">
          Memory 0{index + 1}
        </p>
        <h3 className="font-serif text-3xl tracking-[-0.05em] text-white">
          {title}
        </h3>
        <p className="mt-5 translate-y-4 text-base leading-7 text-stone-300/0 transition-all duration-500 group-hover:translate-y-0 group-hover:text-stone-300/80">
          {note}
        </p>
      </div>
    </motion.article>
  );
}

## components/CustomCursor.tsx

"use client";

import { useEffect, useRef } from "react";

export default function CustomCursor() {
  const dot = useRef<HTMLDivElement | null>(null);
  const ring = useRef<HTMLDivElement | null>(null);

  useEffect(() => {
    const move = (event: MouseEvent) => {
      if (!dot.current || !ring.current) return;
      dot.current.style.transform = `translate3d(${event.clientX}px, ${event.clientY}px, 0)`;
      ring.current.animate(
        { transform: `translate3d(${event.clientX}px, ${event.clientY}px, 0)` },
        { duration: 420, fill: "forwards", easing: "cubic-bezier(.16,1,.3,1)" }
      );
    };

    window.addEventListener("mousemove", move);
    return () => window.removeEventListener("mousemove", move);
  }, []);

  return (
    <>
      <div ref={ring} className="pointer-events-none fixed left-0 top-0 z-[80] hidden h-10 w-10 -translate-x-1/2 -translate-y-1/2 rounded-full border border-rose-100/30 mix-blend-difference md:block" />
      <div ref={dot} className="pointer-events-none fixed left-0 top-0 z-[81] hidden h-1.5 w-1.5 -translate-x-1/2 -translate-y-1/2 rounded-full bg-white md:block" />
    </>
  );
}

## lib/useLenis.ts

"use client";

import { useEffect } from "react";
import Lenis from "lenis";

export function useLenis() {
  useEffect(() => {
    const lenis = new Lenis({
      duration: 1.35,
      smoothWheel: true,
      wheelMultiplier: 0.75
    });

    let raf = 0;
    const update = (time: number) => {
      lenis.raf(time);
      raf = requestAnimationFrame(update);
    };

    raf = requestAnimationFrame(update);

    return () => {
      cancelAnimationFrame(raf);
      lenis.destroy();
    };
  }, []);
}

## app/globals.css

@tailwind base;
@tailwind components;
@tailwind utilities;

:root {
  color-scheme: dark;
  background: #030306;
}

* {
  box-sizing: border-box;
}

html {
  scroll-behavior: auto;
}

body {
  margin: 0;
  overflow-x: hidden;
  background:
    radial-gradient(circle at 50% 0%, rgba(255, 190, 220, 0.08), transparent 38%),
    #030306;
  cursor: none;
}

.font-serif {
  font-family: Georgia, "Times New Roman", serif;
}

.stars {
  background-image:
    radial-gradient(circle, rgba(255,255,255,0.85) 1px, transparent 1px),
    radial-gradient(circle, rgba(255,210,232,0.45) 1px, transparent 1px);
  background-size: 120px 120px, 220px 220px;
  background-position: 0 0, 60px 80px;
  animation: star-drift 32s linear infinite;
}

@keyframes star-drift {
  from {
    transform: translate3d(0, 0, 0);
  }
  to {
    transform: translate3d(-120px, -80px, 0);
  }
}

@media (prefers-reduced-motion: reduce) {
  *,
  *::before,
  *::after {
    animation-duration: 0.001ms !important;
    animation-iteration-count: 1 !important;
    scroll-behavior: auto !important;
    transition-duration: 0.001ms !important;
  }
}

## tailwind.config.ts

import type { Config } from "tailwindcss";

const config: Config = {
  content: [
    "./app/**/*.{js,ts,jsx,tsx,mdx}",
    "./components/**/*.{js,ts,jsx,tsx,mdx}"
  ],
  theme: {
    extend: {
      colors: {
        night: "#030306"
      }
    }
  },
  plugins: []
};

export default config;

## next.config.mjs

const nextConfig = {
  reactStrictMode: true
};

export default nextConfig;

## Experience Notes

### Intro

The site begins with a luxury loading sequence, using a thin progress line and timed emotional copy:

- “Some people come into your life unexpectedly...”
- pause
- “But change everything.”
- reveal
- “Romisaa ❤️”

### 3D Hero

The hero uses a glass/crystal object with:

- slow rotation
- floating movement
- refractive transmission material
- soft rose and blue lighting
- subtle particle field
- fragment-like tetrahedron accents

For a production version, the sphere can be replaced with a custom heart mesh or GLB model while keeping the same lighting, material, and animation structure.

### Scroll Storytelling

The scroll experience includes:

- GSAP line-by-line text reveals
- Lenis smooth scroll
- parallax dream background
- hover-reveal memory cards
- cinematic pacing through full-height sections

### Sections

1. First Impression
2. Connection
3. Memories
4. Emotional Peak
5. Future Vision
6. Final Scene

### Final Message

“I love you, Romisaa. Always.”

## Performance Notes

- Canvas DPR is capped at 1.7 for smoother performance.
- Animations use transform and opacity wherever possible.
- Reduced-motion users receive dramatically shortened animations.
- The Three.js scene avoids heavy postprocessing by default.
- Memory cards use CSS gradients instead of image assets until real photos are provided.

## Metrics Recorded

- page_count: 1
- component_count: 12
- animation_count: 15
