--- src/components/icons.tsx (原始)
type P = { className?: string };

const base = (className?: string) => ({
  className,
  viewBox: "0 0 24 24",
  fill: "none",
  stroke: "currentColor",
  strokeWidth: 1.7,
  strokeLinecap: "round" as const,
  strokeLinejoin: "round" as const,
});

export function LogoMark({ className }: P) {
  return (
    <svg className={className} viewBox="0 0 32 32" fill="none">
      <rect width="32" height="32" rx="8" fill="#C8F04B" />
      <path d="M18.5 4 8 18h6l-2.5 10L22 13h-6l2.5-9z" fill="#0B100D" />
    </svg>
  );
}

export function IconBolt({ className }: P) {
  return (
    <svg className={className} viewBox="0 0 24 24" fill="currentColor">
      <path d="M13 2 4 14h6l-1 8 9-12h-6l1-8z" />
    </svg>
  );
}

export function IconWatch({ className }: P) {
  return (
    <svg {...base(className)}>
      <rect x="7" y="6.2" width="10" height="11.6" rx="3" />
      <path d="M9 6V3h6v3M9 18v3h6v-3M12 10v2.4l1.8 1" />
    </svg>
  );
}

export function IconRun({ className }: P) {
  return (
    <svg {...base(className)}>
      <path d="M3 16.5h18v-.8c0-1.2-1.1-2.1-3-2.5l-3.8-.8-2.4-2.9H8.6L7.4 13 3 14.9v1.6z" />
      <path d="M3 19h18M9.5 13.2l1.6 1.3 2-.4" />
    </svg>
  );
}

export function IconBike({ className }: P) {
  return (
    <svg {...base(className)}>
      <circle cx="5.8" cy="16.5" r="3.3" />
      <circle cx="18.2" cy="16.5" r="3.3" />
      <path d="M5.8 16.5 9.4 9h5.4l3.4 7.5M9.4 9 12 16.5H5.8M14.8 9l-1-2.6h-2.6M13.2 5.2h3" />
    </svg>
  );
}

export function IconDumbbell({ className }: P) {
  return (
    <svg {...base(className)}>
      <path d="M7.5 7.5v9M16.5 7.5v9M4 9.8v4.4M20 9.8v4.4M7.5 12h9M2 12h2M20 12h2" />
    </svg>
  );
}

export function IconMountain({ className }: P) {
  return (
    <svg {...base(className)}>
      <path d="M3 19 9.2 7.6l3.9 6.2 2.4-3.3L21 19H3z" />
      <path d="M8 10l1.2 1.8L10.5 10" />
    </svg>
  );
}

export function IconSwim({ className }: P) {
  return (
    <svg {...base(className)}>
      <circle cx="16.5" cy="6.8" r="2" />
      <path d="M4.5 12.5 9 9.6l4.5 2.9M2.5 17.5c1.9-1.8 3.8-1.8 5.7 0s3.8 1.8 5.7 0 3.8-1.8 5.7 0" />
    </svg>
  );
}

export function IconHeart({ className }: P) {
  return (
    <svg className={className} viewBox="0 0 24 24" fill="currentColor">
      <path d="M12 20.2S4.8 15.7 3 11.2C1.7 8 3.8 4.5 7 4.5c2 0 3.5 1.2 5 3.1 1.5-1.9 3-3.1 5-3.1 3.2 0 5.3 3.5 4 6.7-1.8 4.5-9 9-9 9z" />
    </svg>
  );
}

export function IconHeartPulse({ className }: P) {
  return (
    <svg {...base(className)}>
      <path d="M12 20S5 15.6 3.2 11.2C2 8.2 4 5 7 5c2 0 3.5 1.2 5 3 1.5-1.8 3-3 5-3 3 0 5 3.2 3.8 6.2C19 15.6 12 20 12 20z" />
      <path d="M5.5 12h3l1.5-2.6 2 4.6 1.5-2h4" />
    </svg>
  );
}

export function IconMoon({ className }: P) {
  return (
    <svg {...base(className)}>
      <path d="M20 14.5A8.5 8.5 0 1 1 9.5 4a7 7 0 0 0 10.5 10.5z" />
    </svg>
  );
}

export function IconDrop({ className }: P) {
  return (
    <svg {...base(className)}>
      <path d="M12 3.2s6 6.6 6 10.8a6 6 0 0 1-12 0c0-4.2 6-10.8 6-10.8z" />
    </svg>
  );
}

export function IconLeaf({ className }: P) {
  return (
    <svg {...base(className)}>
      <path d="M5.5 18.5C5.5 9.5 12.5 5 20 5c0 8-4.5 14.5-13 13.5" />
      <path d="M4 20c3-5.5 7-9 11-11" />
    </svg>
  );
}

export function IconGps({ className }: P) {
  return (
    <svg {...base(className)}>
      <circle cx="12" cy="13" r="1.8" fill="currentColor" stroke="none" />
      <path d="M8.5 9.5a5 5 0 0 1 7 0M5.8 6.7a9 9 0 0 1 12.4 0M12 15v5" />
    </svg>
  );
}

export function IconCheck({ className }: P) {
  return (
    <svg {...base(className)}>
      <path d="M5 12.5l4.5 4.5L19 7.5" />
    </svg>
  );
}

export function IconArrowDown({ className }: P) {
  return (
    <svg {...base(className)}>
      <path d="M12 4v15m0 0 6-6m-6 6-6-6" />
    </svg>
  );
}

export function IconArrowRight({ className }: P) {
  return (
    <svg {...base(className)}>
      <path d="M4 12h15m0 0-6-6m6 6-6 6" />
    </svg>
  );
}

export function IconPlay({ className }: P) {
  return (
    <svg className={className} viewBox="0 0 24 24" fill="currentColor">
      <path d="M8 5.5v13l11-6.5-11-6.5z" />
    </svg>
  );
}

export function IconPause({ className }: P) {
  return (
    <svg className={className} viewBox="0 0 24 24" fill="currentColor">
      <rect x="7" y="5" width="3.4" height="14" rx="1" />
      <rect x="13.6" y="5" width="3.4" height="14" rx="1" />
    </svg>
  );
}

export function IconShare({ className }: P) {
  return (
    <svg {...base(className)}>
      <circle cx="6" cy="12" r="2.6" />
      <circle cx="17.5" cy="5.5" r="2.6" />
      <circle cx="17.5" cy="18.5" r="2.6" />
      <path d="M8.4 10.8l6.8-4M8.4 13.2l6.8 4" />
    </svg>
  );
}

/* ---------- brand glyphs ---------- */

export function IconGoogle({ className }: P) {
  return (
    <svg className={className} viewBox="0 0 24 24">
      <path
        fill="#4285F4"
        d="M23.5 12.27c0-.85-.08-1.66-.22-2.45H12v4.64h6.46a5.53 5.53 0 0 1-2.4 3.63v3h3.86c2.26-2.09 3.58-5.17 3.58-8.82z"
      />
      <path
        fill="#34A853"
        d="M12 24c3.24 0 5.96-1.07 7.94-2.91l-3.86-3c-1.07.72-2.44 1.15-4.08 1.15-3.13 0-5.78-2.11-6.73-4.96H1.29v3.09A12 12 0 0 0 12 24z"
      />
      <path
        fill="#FBBC05"
        d="M5.27 14.28A7.2 7.2 0 0 1 4.9 12c0-.79.14-1.56.37-2.28V6.63H1.29a12 12 0 0 0 0 10.74l3.98-3.09z"
      />
      <path
        fill="#EA4335"
        d="M12 4.76c1.76 0 3.34.6 4.58 1.79l3.42-3.42C17.95 1.19 15.24 0 12 0A12 12 0 0 0 1.29 6.63l3.98 3.09C6.22 6.87 8.87 4.76 12 4.76z"
      />
    </svg>
  );
}

export function IconFacebook({ className }: P) {
  return (
    <svg className={className} viewBox="0 0 24 24">
      <circle cx="12" cy="12" r="12" fill="#1877F2" />
      <path
        fill="#EFEBE0"
        d="M13.6 20.5v-6.6h2.2l.33-2.6H13.6V9.6c0-.75.2-1.26 1.28-1.26h1.37V6c-.24-.03-1.05-.1-2-.1-2 0-3.36 1.22-3.36 3.45v1.95H8.6v2.6h2.29v6.6h2.71z"
      />
    </svg>
  );
}

export function IconInstagram({ className }: P) {
  return (
    <svg {...base(className)}>
      <rect x="3.5" y="3.5" width="17" height="17" rx="5" />
      <circle cx="12" cy="12" r="4" />
      <circle cx="17.2" cy="6.8" r="1.1" fill="currentColor" stroke="none" />
    </svg>
  );
}

export function IconWhatsApp({ className }: P) {
  return (
    <svg className={className} viewBox="0 0 24 24">
      <path
        fill="#25D366"
        d="M12 2a10 10 0 0 0-8.63 15.06L2 22l5.1-1.33A10 10 0 1 0 12 2z"
      />
      <path
        fill="#EFEBE0"
        d="M9.1 7.3c-.35 0-.75.13-.95.63-.75 1.25-.4 3 1.05 4.85 1.45 1.85 3.3 3.15 5.15 3.45 1 .15 1.95-.25 2.35-1.1l.35-.75-2.25-1.1-.9.7c-1-.45-2.15-1.65-2.6-2.65l.7-.95-1.1-2.3-1.8-.75z"
      />
    </svg>
  );
}

export function IconXBrand({ className }: P) {
  return (
    <svg className={className} viewBox="0 0 24 24" fill="currentColor">
      <path d="M4 4h3.4l4.5 5.8L16.9 4H20l-6.6 7.6L20.5 20h-3.4l-4.9-6.3L6.9 20H3.8l7-8.1L4 4z" />
    </svg>
  );
}

export function IconApple({ className }: P) {
  return (
    <svg className={className} viewBox="0 0 24 24" fill="currentColor">
      <path d="M16.9 12.9c0-2.4 2-3.55 2.1-3.65-1.15-1.7-2.95-1.9-3.6-1.95-1.5-.15-2.95.9-3.7.9-.8 0-1.95-.9-3.2-.85-1.65 0-3.15.95-4 2.45-1.7 2.95-.45 7.35 1.25 9.75.8 1.2 1.8 2.5 3.05 2.45 1.2 0 1.65-.8 3.15-.8s1.9.8 3.2.75c1.3 0 2.2-1.2 3-2.4.95-1.35 1.35-2.7 1.35-2.75-.05-.05-2.6-1-2.6-3.95zM14.5 5.5c.65-.8 1.1-1.95 1-3.1-1 .05-2.15.7-2.85 1.5-.6.7-1.2 1.85-1.05 2.95 1.1.1 2.25-.55 2.9-1.35z" />
    </svg>
  );
}

export function IconGPlay({ className }: P) {
  return (
    <svg className={className} viewBox="0 0 24 24">
      <path fill="#59D9C9" d="M4.3 2.9 13.6 12l-9.3 9.1c-.2-.2-.3-.5-.3-.9V3.8c0-.4.1-.7.3-.9z" />
      <path fill="#C8F04B" d="M4.3 2.9c.3-.3.8-.3 1.3 0l11 6.2-2.9 2.9L4.3 2.9z" />
      <path fill="#FF5D3B" d="M16.6 9.1 19.7 11c.9.5.9 1.7 0 2.2l-3.1 1.8-3-3 3-2.9z" />
      <path fill="#F5B840" d="M4.3 21.1l9.4-9.1 2.9 2.9-11 6.2c-.5.3-1 .3-1.3 0z" />
    </svg>
  );
}


+++ src/components/icons.tsx (修改后)
type P = { className?: string };

const base = (className?: string) => ({
  className,
  viewBox: "0 0 24 24",
  fill: "none",
  stroke: "currentColor",
  strokeWidth: 1.7,
  strokeLinecap: "round" as const,
  strokeLinejoin: "round" as const,
});

export function LogoMark({ className }: P) {
  return (
    <svg className={className} viewBox="0 0 32 32" fill="none">
      <rect width="32" height="32" rx="8" fill="#C8F04B" />
      <path d="M18.5 4 8 18h6l-2.5 10L22 13h-6l2.5-9z" fill="#0B100D" />
    </svg>
  );
}

export function IconBolt({ className }: P) {
  return (
    <svg className={className} viewBox="0 0 24 24" fill="currentColor">
      <path d="M13 2 4 14h6l-1 8 9-12h-6l1-8z" />
    </svg>
  );
}

export function IconWatch({ className }: P) {
  return (
    <svg {...base(className)}>
      <rect x="7" y="6.2" width="10" height="11.6" rx="3" />
      <path d="M9 6V3h6v3M9 18v3h6v-3M12 10v2.4l1.8 1" />
    </svg>
  );
}

export function IconRun({ className }: P) {
  return (
    <svg {...base(className)}>
      <path d="M3 16.5h18v-.8c0-1.2-1.1-2.1-3-2.5l-3.8-.8-2.4-2.9H8.6L7.4 13 3 14.9v1.6z" />
      <path d="M3 19h18M9.5 13.2l1.6 1.3 2-.4" />
    </svg>
  );
}

export function IconBike({ className }: P) {
  return (
    <svg {...base(className)}>
      <circle cx="5.8" cy="16.5" r="3.3" />
      <circle cx="18.2" cy="16.5" r="3.3" />
      <path d="M5.8 16.5 9.4 9h5.4l3.4 7.5M9.4 9 12 16.5H5.8M14.8 9l-1-2.6h-2.6M13.2 5.2h3" />
    </svg>
  );
}

export function IconDumbbell({ className }: P) {
  return (
    <svg {...base(className)}>
      <path d="M7.5 7.5v9M16.5 7.5v9M4 9.8v4.4M20 9.8v4.4M7.5 12h9M2 12h2M20 12h2" />
    </svg>
  );
}

export function IconMountain({ className }: P) {
  return (
    <svg {...base(className)}>
      <path d="M3 19 9.2 7.6l3.9 6.2 2.4-3.3L21 19H3z" />
      <path d="M8 10l1.2 1.8L10.5 10" />
    </svg>
  );
}

export function IconSwim({ className }: P) {
  return (
    <svg {...base(className)}>
      <circle cx="16.5" cy="6.8" r="2" />
      <path d="M4.5 12.5 9 9.6l4.5 2.9M2.5 17.5c1.9-1.8 3.8-1.8 5.7 0s3.8 1.8 5.7 0 3.8-1.8 5.7 0" />
    </svg>
  );
}

export function IconHeart({ className }: P) {
  return (
    <svg className={className} viewBox="0 0 24 24" fill="currentColor">
      <path d="M12 20.2S4.8 15.7 3 11.2C1.7 8 3.8 4.5 7 4.5c2 0 3.5 1.2 5 3.1 1.5-1.9 3-3.1 5-3.1 3.2 0 5.3 3.5 4 6.7-1.8 4.5-9 9-9 9z" />
    </svg>
  );
}

export function IconHeartPulse({ className }: P) {
  return (
    <svg {...base(className)}>
      <path d="M12 20S5 15.6 3.2 11.2C2 8.2 4 5 7 5c2 0 3.5 1.2 5 3 1.5-1.8 3-3 5-3 3 0 5 3.2 3.8 6.2C19 15.6 12 20 12 20z" />
      <path d="M5.5 12h3l1.5-2.6 2 4.6 1.5-2h4" />
    </svg>
  );
}

export function IconMoon({ className }: P) {
  return (
    <svg {...base(className)}>
      <path d="M20 14.5A8.5 8.5 0 1 1 9.5 4a7 7 0 0 0 10.5 10.5z" />
    </svg>
  );
}

export function IconDrop({ className }: P) {
  return (
    <svg {...base(className)}>
      <path d="M12 3.2s6 6.6 6 10.8a6 6 0 0 1-12 0c0-4.2 6-10.8 6-10.8z" />
    </svg>
  );
}

export function IconLeaf({ className }: P) {
  return (
    <svg {...base(className)}>
      <path d="M5.5 18.5C5.5 9.5 12.5 5 20 5c0 8-4.5 14.5-13 13.5" />
      <path d="M4 20c3-5.5 7-9 11-11" />
    </svg>
  );
}

export function IconGps({ className }: P) {
  return (
    <svg {...base(className)}>
      <circle cx="12" cy="13" r="1.8" fill="currentColor" stroke="none" />
      <path d="M8.5 9.5a5 5 0 0 1 7 0M5.8 6.7a9 9 0 0 1 12.4 0M12 15v5" />
    </svg>
  );
}

export function IconCheck({ className }: P) {
  return (
    <svg {...base(className)}>
      <path d="M5 12.5l4.5 4.5L19 7.5" />
    </svg>
  );
}

export function IconArrowDown({ className }: P) {
  return (
    <svg {...base(className)}>
      <path d="M12 4v15m0 0 6-6m-6 6-6-6" />
    </svg>
  );
}

export function IconArrowRight({ className }: P) {
  return (
    <svg {...base(className)}>
      <path d="M4 12h15m0 0-6-6m6 6-6 6" />
    </svg>
  );
}

export function IconDownload({ className }: P) {
  return (
    <svg {...base(className)}>
      <path d="M12 4v10m0 0 4-4m-4 4-4-4M5 16v2.5A1.5 1.5 0 0 0 6.5 20h11a1.5 1.5 0 0 0 1.5-1.5V16" />
    </svg>
  );
}

export function IconPhone({ className }: P) {
  return (
    <svg {...base(className)}>
      <rect x="7" y="2.8" width="10" height="18.4" rx="2.6" />
      <path d="M10.5 18.4h3" />
    </svg>
  );
}

export function IconPlay({ className }: P) {
  return (
    <svg className={className} viewBox="0 0 24 24" fill="currentColor">
      <path d="M8 5.5v13l11-6.5-11-6.5z" />
    </svg>
  );
}

export function IconPause({ className }: P) {
  return (
    <svg className={className} viewBox="0 0 24 24" fill="currentColor">
      <rect x="7" y="5" width="3.4" height="14" rx="1" />
      <rect x="13.6" y="5" width="3.4" height="14" rx="1" />
    </svg>
  );
}

export function IconShare({ className }: P) {
  return (
    <svg {...base(className)}>
      <circle cx="6" cy="12" r="2.6" />
      <circle cx="17.5" cy="5.5" r="2.6" />
      <circle cx="17.5" cy="18.5" r="2.6" />
      <path d="M8.4 10.8l6.8-4M8.4 13.2l6.8 4" />
    </svg>
  );
}

/* ---------- brand glyphs ---------- */

export function IconGoogle({ className }: P) {
  return (
    <svg className={className} viewBox="0 0 24 24">
      <path
        fill="#4285F4"
        d="M23.5 12.27c0-.85-.08-1.66-.22-2.45H12v4.64h6.46a5.53 5.53 0 0 1-2.4 3.63v3h3.86c2.26-2.09 3.58-5.17 3.58-8.82z"
      />
      <path
        fill="#34A853"
        d="M12 24c3.24 0 5.96-1.07 7.94-2.91l-3.86-3c-1.07.72-2.44 1.15-4.08 1.15-3.13 0-5.78-2.11-6.73-4.96H1.29v3.09A12 12 0 0 0 12 24z"
      />
      <path
        fill="#FBBC05"
        d="M5.27 14.28A7.2 7.2 0 0 1 4.9 12c0-.79.14-1.56.37-2.28V6.63H1.29a12 12 0 0 0 0 10.74l3.98-3.09z"
      />
      <path
        fill="#EA4335"
        d="M12 4.76c1.76 0 3.34.6 4.58 1.79l3.42-3.42C17.95 1.19 15.24 0 12 0A12 12 0 0 0 1.29 6.63l3.98 3.09C6.22 6.87 8.87 4.76 12 4.76z"
      />
    </svg>
  );
}

export function IconFacebook({ className }: P) {
  return (
    <svg className={className} viewBox="0 0 24 24">
      <circle cx="12" cy="12" r="12" fill="#1877F2" />
      <path
        fill="#EFEBE0"
        d="M13.6 20.5v-6.6h2.2l.33-2.6H13.6V9.6c0-.75.2-1.26 1.28-1.26h1.37V6c-.24-.03-1.05-.1-2-.1-2 0-3.36 1.22-3.36 3.45v1.95H8.6v2.6h2.29v6.6h2.71z"
      />
    </svg>
  );
}

export function IconInstagram({ className }: P) {
  return (
    <svg {...base(className)}>
      <rect x="3.5" y="3.5" width="17" height="17" rx="5" />
      <circle cx="12" cy="12" r="4" />
      <circle cx="17.2" cy="6.8" r="1.1" fill="currentColor" stroke="none" />
    </svg>
  );
}

export function IconWhatsApp({ className }: P) {
  return (
    <svg className={className} viewBox="0 0 24 24">
      <path
        fill="#25D366"
        d="M12 2a10 10 0 0 0-8.63 15.06L2 22l5.1-1.33A10 10 0 1 0 12 2z"
      />
      <path
        fill="#EFEBE0"
        d="M9.1 7.3c-.35 0-.75.13-.95.63-.75 1.25-.4 3 1.05 4.85 1.45 1.85 3.3 3.15 5.15 3.45 1 .15 1.95-.25 2.35-1.1l.35-.75-2.25-1.1-.9.7c-1-.45-2.15-1.65-2.6-2.65l.7-.95-1.1-2.3-1.8-.75z"
      />
    </svg>
  );
}

export function IconXBrand({ className }: P) {
  return (
    <svg className={className} viewBox="0 0 24 24" fill="currentColor">
      <path d="M4 4h3.4l4.5 5.8L16.9 4H20l-6.6 7.6L20.5 20h-3.4l-4.9-6.3L6.9 20H3.8l7-8.1L4 4z" />
    </svg>
  );
}

export function IconApple({ className }: P) {
  return (
    <svg className={className} viewBox="0 0 24 24" fill="currentColor">
      <path d="M16.9 12.9c0-2.4 2-3.55 2.1-3.65-1.15-1.7-2.95-1.9-3.6-1.95-1.5-.15-2.95.9-3.7.9-.8 0-1.95-.9-3.2-.85-1.65 0-3.15.95-4 2.45-1.7 2.95-.45 7.35 1.25 9.75.8 1.2 1.8 2.5 3.05 2.45 1.2 0 1.65-.8 3.15-.8s1.9.8 3.2.75c1.3 0 2.2-1.2 3-2.4.95-1.35 1.35-2.7 1.35-2.75-.05-.05-2.6-1-2.6-3.95zM14.5 5.5c.65-.8 1.1-1.95 1-3.1-1 .05-2.15.7-2.85 1.5-.6.7-1.2 1.85-1.05 2.95 1.1.1 2.25-.55 2.9-1.35z" />
    </svg>
  );
}

export function IconGPlay({ className }: P) {
  return (
    <svg className={className} viewBox="0 0 24 24">
      <path fill="#59D9C9" d="M4.3 2.9 13.6 12l-9.3 9.1c-.2-.2-.3-.5-.3-.9V3.8c0-.4.1-.7.3-.9z" />
      <path fill="#C8F04B" d="M4.3 2.9c.3-.3.8-.3 1.3 0l11 6.2-2.9 2.9L4.3 2.9z" />
      <path fill="#FF5D3B" d="M16.6 9.1 19.7 11c.9.5.9 1.7 0 2.2l-3.1 1.8-3-3 3-2.9z" />
      <path fill="#F5B840" d="M4.3 21.1l9.4-9.1 2.9 2.9-11 6.2c-.5.3-1 .3-1.3 0z" />
    </svg>
  );
}
# jampfit
App treino
