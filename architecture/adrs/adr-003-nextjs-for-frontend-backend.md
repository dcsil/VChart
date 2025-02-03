## ADR 003: Next.js for Frontend and Backend

## Context
We plan to develop a web application that automatically generates structured medical charts from voice recordings, allowing users to review and edit these charts on both mobile and desktop devices. To achieve this, we require a development framework that supports cross-platform accessibility.

Two primary approaches exist for achieving this. 

One, we can use native frameworks (e.g. Flutter, React Native) that allow us to develop software that can be installed on both mobile and desktop devices.

On the other hand, we can also use web frameworks (e.g. React.js, Next.js, Vue.js, Django, Express.js) that allow us to develop a web application that is accessible from any browser.

A key difference between these approaches is that native frameworks provide access to device-specific features such as GPS, notifications, and the camera, and they can function offline. However, native applications tend to have larger file sizes and slower iteration cycles due to the need for app store approvals.

### Options
React.js, React Native, Vue.js, Express.js, Flutter, Django

## Decision
We will use Next.js for our frontend/backend framework.

## Status
Accepted.

## Consequences
We chose a web framework over a native framework because we do not require the advantages offered by native applications. Specifically, we do not need access to mobile device features such as GPS or the camera, and our transcription and LLM services already require an internet connection, so offline functionality is unnecessary. In addition, our team has more experience with web development, which will allow us to develop the MVP faster. 

We selected Next.js over React.js because React.js relies solely on client-side rendering (CSR), which may lead to performance issues, especially in hospitals that still use outdated systems and devices. Next.js supports server-side rendering (SSR), which helps improve performance and ensures better accessibility across a wider range of possible devices.