---
layout: page
title: Documentation
permalink: /docs/
---

# Documentation

## Getting Started

### Installation
1. Download "Solve It Now!" from the Apple App Store
2. Open the app on your iOS device
3. The app will start with a tutorial explaining the workflow options
4. Begin with the example problems to learn the methodology

### System Requirements
- iOS 14.0 or later
- Compatible with iPhone, iPad, and iPod touch
- Internet connection required for AI-powered workflows
- Approximately 50MB of storage space

## User Guide

### Understanding the Problem-Solving Framework

The app uses a systematic methodology based on professional troubleshooting practices:

1. **Problem Statement** - Define what's wrong with what object
2. **IS/IS NOT Analysis** - Document problem boundaries
3. **Dimensional Analysis** - Investigate WHAT, WHERE, WHEN, EXTENT
4. **AI Analysis** - Generate solutions and diagnostic questions
5. **Validation** - Evaluate and refine solutions

### Main Interface Overview

#### **Problem Specification Area**
The main scrollable area where you:
- Enter your problem statement in "Object/Defect" format
- Fill in WHAT, WHERE, WHEN, and EXTENT sections
- View suggested solutions (after AI analysis)
- See diagnostic questions (after AI analysis)

#### **Solve Panel**
The bottom action area containing:
- **Solve Button** - Triggers AI analysis of your problem specification
- **Workflow Selector** - Choose between different AI processing modes
- **Examples Menu** - Access built-in problem examples
- **Export/Import** - Share or save your problem documents

### Step-by-Step Workflow

#### **1. Define Your Problem**
- Tap in the problem statement field
- Use the format: "What object has what defect"
- Example: "My car does not start on cold mornings"
- Be specific and focus on observable symptoms

#### **2. Complete the Analysis Sections**

**WHAT Section:**
- WHAT IS: List things that have the problem and what's wrong
- WHAT IS NOT: List similar things that don't have the problem

**WHERE Section:**
- WHERE IS: Location where problem occurs, position on the object
- WHERE IS NOT: Places where you'd expect to see the problem but don't

**WHEN Section:**
- WHEN IS: When problem first noticed, patterns in timing
- WHEN IS NOT: Times when problem could occur but doesn't

**EXTENT Section:**
- EXTENT IS: How many objects affected, severity, trends
- EXTENT IS NOT: How many could be affected but aren't

#### **3. Choose Your AI Workflow**

**System Prompt Workflow:**
- Generates a formatted prompt for use with your own AI tools
- App copies prompt to clipboard for pasting elsewhere
- Full control over AI interaction
- No data sent to external services

**Public AI Workflow:**
- Direct integration with AI services
- Your data may be used to improve AI models
- Immediate results within the app
- No additional cost

**Private AI Workflow (Premium):**
- AI analysis with privacy guarantee
- Your data is not used for training
- Requires subscription purchase
- Same immediate results as Public AI

#### **4. Review AI Suggestions**

After AI analysis, you'll see:

**Suggested Solutions:**
- List of potential solutions to validate
- Tap to navigate to detailed evaluation
- Accept, reject, or mark as "not sure"
- Accepted solutions appear in main view

**Diagnostic Questions:**
- Follow-up questions for deeper investigation  
- Answer questions to refine your understanding
- Questions help validate or eliminate potential causes

#### **5. Evaluate and Refine**

**Solution Evaluation:**
- Review each suggested solution carefully
- Consider feasibility, cost, and likelihood of success
- Use Accept/Reject/Not Sure buttons
- Focus on solutions that address root causes

**Answer Diagnostic Questions:**
- Navigate to diagnostic questions section
- Answer each question based on your investigation
- Use the text editor to provide detailed responses
- Questions help eliminate false leads and confirm hypotheses

### Built-in Examples

#### **Donut Factory Problem**
A manufacturing scenario demonstrating:
- How scaling can reveal hidden single-point failures
- The importance of per-component validation
- Pattern recognition in intermittent problems
- System-level thinking for complex issues

**Key Learning Points:**
- One faulty machine out of 10 affects only plain donuts
- Scale masks problems that exist at smaller volumes
- Different product lines may use different equipment
- Quality checks needed at each process stage

#### **Computer Crash Problem**
A real technical case study showing:
- Multi-layer system analysis (hardware/software/firmware)
- How new components can introduce subtle issues
- The challenge of intermittent hardware problems
- Professional debugging methodologies

**Key Learning Points:**
- 2018 MacBooks vs 2017 models - new T2 chip introduction
- Problem occurs only during sleep/wake cycles
- Hardware replacement doesn't fix software issues
- Deep system knowledge required for complex problems

### Advanced Features

#### **Document Management**
- **Export**: Share problem documents as files
- **Import**: Load previously saved problems
- **Templates**: Start from example problems
- **Version Control**: Track changes to your analysis

#### **Workflow Customization**
- Choose AI processing mode in settings
- Switch between workflows for different problems
- Balance privacy needs with convenience
- Adapt to your organization's AI policies

## Tips & Best Practices

### **Effective Problem Definition**
- Focus on observable, measurable symptoms
- Avoid assumptions about causes
- Use specific, concrete language
- Separate symptoms from root causes

### **IS/IS NOT Analysis**
- Be thorough in documenting boundaries
- Look for patterns in what's excluded
- Consider similar situations without problems
- Use comparisons to narrow the scope

### **Working with AI Suggestions**
- Treat suggestions as starting points, not final answers
- Validate suggestions against your specific context
- Consider implementation feasibility
- Look for solutions that address root causes

### **Diagnostic Questions**
- Answer questions based on actual investigation
- Be honest about what you don't know
- Use questions to guide further data collection
- Document your findings for future reference

## Troubleshooting

### **Common Issues**

**App won't start:**
- Ensure iOS is up to date
- Restart your device
- Reinstall the app if needed

**AI analysis fails:**
- Check internet connection
- Verify problem specification is complete
- Try different AI workflow
- Contact support if issues persist

**Subscription issues:**
- Verify purchase in App Store settings
- Restore purchases if needed
- Check subscription status
- Contact Apple Support for billing issues

**Performance issues:**
- Close other apps to free memory
- Restart the app
- Check available storage space
- Clear app cache by reinstalling

### **Getting Better Results**

**Problem Specification:**
- Include more detail in IS/IS NOT sections
- Provide specific examples and timeframes  
- Use measurable criteria where possible
- Consider multiple perspectives on the problem

**AI Workflow Selection:**
- Use System Prompt for sensitive data
- Try Public AI for general problems
- Upgrade to Private AI for business-critical issues
- Experiment with different approaches

## Support

Need additional help? Contact us through:
- In-app support system
- [GitHub repository](https://github.com/faisalmemon/solve-it-now) issues
- App Store reviews (for general feedback)
- Direct support email (available in app)

## Privacy Policy

- **System Prompt Mode**: No data leaves your device
- **Public AI Mode**: Data sent to AI providers may be used for training
- **Private AI Mode**: Data processed but not used for training
- **Local Storage**: All documents stored locally on your device
- **Analytics**: Only anonymous usage statistics collected

---

*Documentation last updated: {{ site.time | date: "%B %d, %Y" }}*
