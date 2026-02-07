# Outbox-Labs-Assignment
Production-grade email scheduling system built with TypeScript, Express, BullMQ, Redis, and Next.js. Supports delayed email scheduling, concurrency control, Redis-backed rate limiting, restart-safe job execution, and a dashboard UI. Built as part of the ReachInbox Full-Stack Hiring Assignment.
This project is a production-style email scheduling system built as part of the ReachInbox Full-Stack Hiring Assignment.

The system allows users to schedule emails for future delivery, processes them using a persistent job queue (BullMQ + Redis), enforces rate limits and delays, and sends emails via Ethereal SMTP. The architecture is designed to survive server restarts without duplicating or losing scheduled jobs.

The project includes:

A TypeScript + Express backend with BullMQ workers

A Next.js frontend dashboard

Redis-backed scheduling and rate limiting

Configurable concurrency and throttling controls
