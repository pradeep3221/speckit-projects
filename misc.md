Spec-Driven Development (SDD) is an engineering methodology where precise, machine-readable specifications—rather than vague prompts—serve as the single source of truth for AI code generation. It uses a structured approach (research, plan, execute) to ensure AI agents produce reliable, compliant code by following a clear blueprint, reducing "vibe coding" unpredictability
	Spec-driven development
	Spec-Driven Development: From Vibe-Coding to AI Engineering
	

Diving Into Spec-Driven Development With GitHub Spec Kit
	github/spec-kit
	fabriqaai/specs.md

Using spec-driven development with Claude Code
Spec-driven development with AI: Get started with a new open source toolkit
Understanding Spec-Driven-Development: Kiro, spec-kit, and Tessl

AI-native development framework | Spec-Driven Development Tools 
	github/spec-kit
	Kiro
	Tessl
	Google Stitch vs figma make
	

Prompt-to-app scaffolding 
SEI - Software Engineering Intelligence
	Professional AI Prompt Library for Software Engineering (comprehensive blueprint )
	
	
Diving Into Spec-Driven Development With GitHub Spec Kit - Microsoft for Developers
https://github.blog/ai-and-ml/generative-ai/spec-driven-development-with-ai-get-started-with-a-new-open-source-toolkit/

GitHub Spec Kit vs BMAD-Method: A Comprehensive Comparison : Part 1


3 places this approach works 
        Greenfield (zero-to-one)
        Brownfield - Feature work in existing systems (N-to-N+1): Iterative Enhancement
        Legacy modernization: Modernize legacy systems

Alternatives
        Speckit
        BMAD
        Open Spec
        Agent OS 
GitHub Spec Kit --> 🤖 Supported AI Agents
        Spec Kit with Claude Code
        Spec Kit + GitHub Copilot (The Integrated Agent)
        
Spec Kit commands (/constitution, /specify, /plan, /tasks, /implement) 
         Figma MCP server

Install python

> uv tool install specify-cli --from git+https://github.com/github/spec-kit.git
> set PATH="C:\\Users\\prade\\.local\\bin;%PATH%"


Open folder in VS code or cmd
        > uv tool list  2>&1
        > uv tool dir --bin  2>&1
        > $env:path = "C:\Users\prade\.local\bin";$env:Path;  specify check or specify version 2>&1

> specify check
> specify init <PROJECT_NAME>   Or specify init PradTinyUrl


Next Steps
        1. Go to the project folder: cd PradTinyUrl                                                                                                                                 
        2. Start using slash commands with your AI agent:  
                a. /speckit.constitution - Establish project principles  
                b. /speckit.specify - Create baseline specification  
                c. /speckit.plan - Create implementation plan  
                d. /speckit.tasks - Generate actionable tasks 
                e. /speckit.implement - Execute implementation           

Enhancement Commands
Optional commands that you can use for your specs (improve quality & confidence)       
        • /speckit.clarify (optional) - Ask structured questions to de-risk ambiguous areas before planning (run before /speckit.plan if used) 
        • /speckit.analyze (optional) - Cross-artifact consistency & alignment report (after /speckit.tasks, before /speckit.implement)  
        • /speckit.checklist (optional) - Generate quality checklists to validate requirements completeness, clarity, and consistency (after /speckit.plan)  

E:\GenerativeAIDev\SpecKit\PradTinyUrl>code .
Goto Github copilot
        1. Consitute: /speckit.constitution
                a. Click / and select speckit-constitution and Add prd (.pdf/md) as context and enter. Or you can select in SetAgent (ctrl+ .) to speckit.constitution.
                        i. To add a Product requirements Document (PRD/SRS/FRS). Capturing problem, scope, users, success criteria and constrains. Key flows, non-functional constraints, out of scope.
                b. Implement the feature specification based on the updated constitution. I want to build…
        2. Specify:  /speckit.specify
                a. Create a plan for the spec. I am building with..
                b. /speckit.clarify (optional) - Clarify spec requirements
        3. Plan: /speckit.plan
                a. To define domain-specific and technical requirement. This include frameworks, libraries, databases, infrastructure, data contracts, and any domain specific rules or standards. 
                        i.  and Domain-Specific requirement - regulatory compliance rules, industry specific data formats or APIs, performance thresholds, integration requirements with existing systems.
                b. Create a technical plan.  I am building with <<.NET 10, Angular, event driven etc.>>
                c. /speckit.checklist (optional) - Create  a checklist
        4. Task: /speckit.tasks
                a. Brea down tasks, decompose the specs and plan into manageable, phased tasks. Each task becomes actionable for AI agent to implement
                b. /speckit.analyze (optional) - run a project analysis for consistency.
        5. Implementation: /speckit.implement
                a. Implement and iterate.
                
                
        


GitHub Spec Kit 💖 GitHub Copilot CLI
E:\GenerativeAIDev\SpecKit\PradTinyUrl>copilot --banner --allow-all-tools
        Copilot CLI --> winget install GitHub.Copilot
        /help
        /login

Type "we are going to use slash command from .github/prompts" 

To add a Product Requirements Document (PRD) and domain-specific requirements using GitHub Spec Kit 
        From PRD to Production: My spec-kit Workflow for Structured Development | by Stephan Eberle | Medium  
        Deep Dive into SpecKit: A Comprehensive Guide to Spec-Driven Development | LPains

The SpecKit Workflow | mohomo70/spec-ecom | DeepWiki
        SpecKit - Workflow Diagram · github/spec-kit · Discussion #468 · GitHub  

How SpecKit Helps Users Track Workflow Status & Progress 
        specify CLI Reference | github/spec-kit | DeepWiki
        The /speckit.analyze Command Shows Status & Issues




<img width="740" height="2553" alt="image" src="https://github.com/user-attachments/assets/11b1617c-e992-450d-8269-190d6eca5138" />
