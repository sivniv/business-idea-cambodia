---
version: alpha
name: Cat AI
description: Premium dark-themed investor pitch for a Phygital Virtual Pet Ecosystem
  in Phnom Penh, Cambodia.
colors:
  primary: '#f59e0b'
  secondary: '#94a3b8'
  tertiary: '#8b5cf6'
  neutral: '#0a0a0f'
  surface: '#12121a'
  surface-hover: '#1a1a26'
  on-primary: '#0a0a0f'
  on-neutral: '#f1f5f9'
  on-surface: '#e2e8f0'
  muted: '#64748b'
  border: rgba(245,158,11,0.12)
  success: '#10b981'
  error: '#ef4444'
  surface-dim: '#131318'
  surface-bright: '#39383e'
  surface-container-lowest: '#0e0e13'
  surface-container-low: '#1b1b20'
  surface-container: '#1f1f25'
  surface-container-high: '#2a292f'
  surface-container-highest: '#35343a'
  on-surface-variant: '#d8c3ad'
  inverse-surface: '#e4e1e9'
  inverse-on-surface: '#303036'
  outline: '#a08e7a'
  outline-variant: '#534434'
  surface-tint: '#ffb95f'
  primary-container: '#f59e0b'
  on-primary-container: '#613b00'
  inverse-primary: '#855300'
  on-secondary: '#233143'
  secondary-container: '#39485a'
  on-secondary-container: '#a7b6cc'
  on-tertiary: '#3c0091'
  tertiary-container: '#bda2ff'
  on-tertiary-container: '#520fbb'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffddb8'
  primary-fixed-dim: '#ffb95f'
  on-primary-fixed: '#2a1700'
  on-primary-fixed-variant: '#653e00'
  secondary-fixed: '#d4e4fa'
  secondary-fixed-dim: '#b9c8de'
  on-secondary-fixed: '#0d1c2d'
  on-secondary-fixed-variant: '#39485a'
  tertiary-fixed: '#e9ddff'
  tertiary-fixed-dim: '#d0bcff'
  on-tertiary-fixed: '#23005c'
  on-tertiary-fixed-variant: '#5516be'
  background: '#131318'
  on-background: '#e4e1e9'
  surface-variant: '#35343a'
  border-amber: rgba(245,158,11,0.12)
typography:
  h1:
    fontFamily: Outfit
    fontSize: 48px
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: -0.02em
  h2:
    fontFamily: Outfit
    fontSize: 32px
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: -0.5px
  h3:
    fontFamily: Outfit
    fontSize: 1rem
    fontWeight: 600
    lineHeight: 1.3
  body-md:
    fontFamily: Rubik
    fontSize: 1rem
    lineHeight: 1.65
    fontWeight: '400'
  body-sm:
    fontFamily: Rubik
    fontSize: 0.875rem
    lineHeight: 1.6
    fontWeight: '400'
  label-caps:
    fontFamily: Outfit
    fontSize: 0.75rem
    fontWeight: 600
    letterSpacing: 0.08em
    textTransform: uppercase
    lineHeight: '1'
  headline-xl:
    fontFamily: Outfit
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Outfit
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.5px
  headline-md:
    fontFamily: Outfit
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: '1.3'
  headline-xl-mobile:
    fontFamily: Outfit
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Outfit
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.2'
rounded:
  sm: 8px
  md: 14px
  lg: 20px
  full: 9999px
  DEFAULT: 0.5rem
  xl: 1.5rem
spacing:
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 48px
  section: 80px
  container-max: 1280px
  gutter: 24px
components:
  button-primary:
    backgroundColor: '{colors.primary}'
    textColor: '{colors.on-primary}'
    rounded: '{rounded.sm}'
    padding: 13px 28px
    fontSize: 0.875rem
    fontWeight: 600
    fontFamily: Rubik
  button-primary-hover:
    backgroundColor: '#d97706'
    textColor: '{colors.on-primary}'
  button-outline:
    backgroundColor: transparent
    textColor: '{colors.on-neutral}'
    borderColor: '{colors.border}'
    rounded: '{rounded.sm}'
    padding: 13px 28px
    fontSize: 0.875rem
    fontWeight: 500
  button-outline-hover:
    borderColor: '{colors.primary}'
    textColor: '{colors.primary}'
  card:
    backgroundColor: '{colors.surface}'
    textColor: '{colors.on-surface}'
    borderColor: '{colors.border}'
    rounded: '{rounded.md}'
    padding: 24px
  card-hover:
    borderColor: rgba(245,158,11,0.3)
    backgroundColor: '{colors.surface-hover}'
  nav-link:
    textColor: '{colors.muted}'
    fontSize: 0.8125rem
    fontWeight: 500
  nav-link-hover:
    textColor: '{colors.primary}'
  badge:
    backgroundColor: rgba(245,158,11,0.08)
    textColor: '{colors.primary}'
    borderColor: '{colors.border}'
    rounded: '{rounded.full}'
    padding: 6px 14px
    fontSize: 0.75rem
  quote-block:
    borderLeftColor: '{colors.primary}'
    backgroundColor: '{colors.surface}'
    padding: 16px 20px
  highlight-box:
    backgroundColor: rgba(245,158,11,0.06)
    borderColor: '{colors.border}'
    rounded: '{rounded.md}'
    padding: 32px
  input:
    backgroundColor: rgba(255,255,255,0.04)
    textColor: '{colors.on-neutral}'
    borderColor: '{colors.border}'
    rounded: '{rounded.sm}'
    padding: 12px 14px
    fontSize: 0.875rem
  submit-btn:
    backgroundColor: '{colors.primary}'
    textColor: '{colors.on-primary}'
    rounded: '{rounded.sm}'
    padding: 14px
    fontSize: 1rem
    fontWeight: 700
---

