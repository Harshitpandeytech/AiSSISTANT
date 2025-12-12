AiSSISTANT

AiSSISTANT is an AI-powered chat application that combines real-time messaging, intelligent writing assistance, and live web search. It is built using Stream Chat, OpenAI, and a modern full-stack architecture.

Features

Real-time chat with Stream Chat

AI writing and content generation using OpenAI

Web search capability via Tavily API

Responsive React UI with light/dark themes

Categorized writing prompts

Dynamic AI agent creation per channel

Secure JWT authentication

Architecture Overview
Backend – 

Node.js + Express server

Stream Chat server integration

OpenAI-based AI response engine

Tavily web search integration

Agent lifecycle management

JWT authentication

Input validation and CORS configuration

Frontend – 

React + TypeScript

Stream Chat React components

Vite build system

Writing prompt interface and AI tools

AI Agent System

Agents are created per chat channel when requested

Each agent initializes an OpenAI assistant with search support

Handles user messages and maintains context

Automatically performs web searches when needed

Agents are cleaned up after inactivity

Security

JWT-based authentication

Environment variable–based secrets

Token expiration and refresh handling

Server-side request validation

Tech Stack
Backend

Node.js

Express

Stream Chat

OpenAI

Tavily API

Axios

TypeScript

Frontend

React

TypeScript

Vite

Stream Chat React

Tailwind CSS

shadcn/ui

React Router

React Hook Form

