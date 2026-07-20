# Flipkart PageSpeed Insights Dashboard

## Overview

This project provides a comprehensive PageSpeed Insights analysis of Flipkart.com using Lighthouse metrics and Core Web Vitals data. The dashboard is designed to evaluate website performance, accessibility, SEO, and best practices while identifying optimization opportunities to improve user experience and search engine rankings.

## Objectives

* Measure overall website performance.
* Analyze Core Web Vitals metrics.
* Evaluate Accessibility, SEO, and Best Practices scores.
* Identify performance bottlenecks.
* Provide actionable recommendations for optimization.

## Tools & Technologies

* Google PageSpeed Insights
* Google Lighthouse
* Microsoft Excel / Google Sheets
* Dashboard Charts & KPI Visualizations

## Key Metrics Analyzed

### Performance

* Performance Score
* First Contentful Paint (FCP)
* Largest Contentful Paint (LCP)
* Speed Index
* Total Blocking Time (TBT)
* Time to Interactive (TTI)

### Accessibility

* Accessibility Score
* Color Contrast Analysis
* ARIA Compliance
* Screen Reader Support

### Best Practices

* Security Checks
* HTTPS Usage
* Browser Compatibility
* Modern Web Standards

### SEO

* SEO Score
* Meta Tags Validation
* Mobile Friendliness
* Search Engine Optimization Checks

### Core Web Vitals

* Largest Contentful Paint (LCP)
* Interaction to Next Paint (INP)
* Cumulative Layout Shift (CLS)

## Current Results

| Metric          | Score  |
| --------------- | ------ |
| Performance     | 36     |
| Accessibility   | 77     |
| Best Practices  | 96     |
| SEO             | 92     |
| Core Web Vitals | Failed |

### Core Web Vitals Details

| Metric | Current Value | Status            | Target  |
| ------ | ------------- | ----------------- | ------- |
| LCP    | 2.6s          | Needs Improvement | ≤ 2.5s  |
| INP    | 501ms         | Poor              | ≤ 200ms |
| CLS    | 0             | Good              | ≤ 0.1   |

## Overall Dashboard Score

| Category       | Score |
| -------------- | ----- |
| Performance    | 76.40 |
| Accessibility  | 77.09 |
| Best Practices | 94.86 |
| SEO            | 96.50 |
| Overall Score  | 86.21 |

## Key Findings

1. Performance score is significantly lower than other categories.
2. INP (Interaction to Next Paint) is the primary bottleneck affecting Core Web Vitals.
3. SEO and Best Practices scores are excellent.
4. Accessibility can be further improved to reach industry standards.
5. Website requires performance optimization to pass Core Web Vitals consistently.

## Recommendations

### High Priority

* Reduce JavaScript execution time.
* Minimize main-thread work.
* Optimize third-party scripts.
* Implement code splitting and lazy loading.

### Medium Priority

* Optimize images using WebP/AVIF formats.
* Enable browser caching.
* Reduce unused CSS and JavaScript.
* Improve server response times.

### Low Priority

* Continue maintaining strong SEO practices.
* Improve accessibility compliance.
* Regularly monitor Core Web Vitals.

## Expected Benefits

* Faster page loading speed.
* Better user experience.
* Improved Core Web Vitals compliance.
* Higher search engine rankings.
* Increased conversion rates and customer engagement.

## Author

Prepared as part of a Flipkart Website Performance Analysis project using Google Lighthouse and PageSpeed Insights data.
