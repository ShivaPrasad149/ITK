# UNIT – II: RPA Platforms
## Exam Preparation Notes (Simple & Detailed)

---

## 1. Components of RPA

### What are the Core Components of Any RPA Platform?

| Component | Purpose | Simple Explanation |
|-----------|---------|------------------|
| **Recorder** | Records user actions on screen | Like a macro recorder in Excel - captures mouse clicks and keyboard typing so robot can replay them |
| **Development Studio** | Where developers create robot instructions | Visual tool to design workflows using drag-and-drop activities (no heavy coding needed) |
| **Plugin/Extension** | Helps robot interact with special applications | Extra tools for apps like Java, SAP where normal methods don't work well |
| **Bot Runner (Robot)** | Executes the automated tasks | The actual "worker" that runs the process you designed |
| **Control Center** | Manages and monitors all robots | Central dashboard to start/stop robots, schedule tasks, manage licenses |

### Why These Components Matter:
- **Recorder** → Makes automation fast and easy (big reason for RPA popularity)
- **Studio** → Lets non-programmers build robots visually
- **Extensions** → Solves tough UI recognition problems
- **Robot** → Does the actual work automatically
- **Control Center** → Manages many robots at enterprise scale

---

## 2. RPA Platforms (Major Vendors)

### Comparison of Key RPA Platforms:

| Platform | Headquarters | Founded | CEO | Key Clients | Best For |
|----------|-------------|---------|-----|-------------|----------|
| **Automation Anywhere** | San Jose, USA | 2003 | Mihir Shukla | Deloitte, Accenture, AT&T, JPMorgan | Structured + unstructured data, cognitive automation |
| **UiPath** | Bucharest, Romania | - | Daniel Dines | Atos, AXA, BBC, SAP, Cognizant | Visual development, easy learning curve |
| **Blue Prism** | United Kingdom | 2001 | Alastair Bathgate | BNY Mellon, RWE npower, Telefonica | Enterprise-scale, centrally managed automation |
| **WorkFusion** | New York, USA | 2011 | Max Yangkelivich, Andrew Volkov | Thomson Reuters, Citi, Standard Bank | High-volume data + machine learning |
| **Thoughtonomy** | London, UK | 2013 | Terry Walby | Atos, Fujitsu, CGI, BT | Custom automation using Blue Prism + others |
| **KOFAX** | Irvine, California | - | Paul Rooke | Arrow Electronics, Delta Dental, Audi | Repetitive rule-based tasks, task prioritization |

### Revenue & Market Focus (Quick Reference):

**Automation Anywhere:**
- Top market: USA (>50% revenue)
- Top industry: BFSI (Banking, Financial Services, Insurance)

**UiPath:**
- Markets: North America, Europe, UK, APAC
- Industries: BFSI, Healthcare, Telecom, Retail

**Blue Prism:**
- Top market: UK (>50% revenue)
- Industries: BFSI, Health, Retail, Telecom, Manufacturing, Public Sector

**WorkFusion:**
- Top market: North America (>80% revenue)
- Top industry: BFSI (~90% revenue)

**KOFAX:**
- Top market: North America (~50% revenue)
- Industries: BFSI, Retail, Travel, Manufacturing, Healthcare

> 📌 **Exam Tip**: Remember: UiPath = visual/easy; Blue Prism = enterprise/centralized; Automation Anywhere = cognitive/data-focused

---

## 3. About UiPath

### Company Overview:
- **Headquarters**: Bucharest, Romania
- **CEO**: Daniel Dines
- **Global Offices**: London, Tokyo, Paris, Singapore, Melbourne, Hong Kong, Bengaluru
- **Growth**: Rapid expansion in revenue and workforce

### UiPath Platform Components:

| Component | Purpose | Key Features |
|-----------|---------|-------------|
| **UiPath Studio** | Design automation processes | Visual flowchart interface, drag-and-drop activities, recorder, error highlighting |
| **UiPath Robot** | Execute designed processes | Works in attended (human-triggered) and unattended (auto-run) modes |
| **UiPath Orchestrator** | Manage and monitor robots | Web-based, deploy multiple robots, schedule tasks, manage queues, store logs |

### UiPath Editions:

| Edition | Best For | Key Features |
|---------|----------|-------------|
| **Enterprise Edition** | Large companies scaling RPA | Integrated with Orchestrator, manual updates via installer |
| **Community Edition** | Individuals, students, small businesses (<$1M revenue or <250 workstations) | Free, auto-updates, no server integration, online activation required, forum support |

> ⚠️ **Note**: Community Edition is for learning only - commercial use requires paid license (contact sales@uipath.com)

---

## 4. The Future of Automation

### Key Concepts:

**Fourth Industrial Revolution:**
- Technology embedded in society and human life
- Includes: Robotics, 3D printing, nanotechnology, IoT, autonomous vehicles
- Will fundamentally change how we live, work, and interact

**Impact on Jobs:**
| Job Type | Automation Risk | Examples |
|----------|----------------|----------|
| **High Risk (~5% of jobs)** | Routine, repetitive, predictable tasks | Telemarketing, data entry, clerical work, retail sales, cashiers, toll booths, fast food |
| **Medium Risk** | Partial automation (some tasks automated) | Most white-collar jobs |
| **Low Risk** | Requires creativity, emotional intelligence, complex reasoning | Strategic roles, creative fields, healthcare, education |

### How to Prepare:
✅ Focus on skills robots can't easily replace:
- Critical thinking and problem-solving
- Emotional intelligence and communication
- Creativity and innovation
- Adaptability and continuous learning

✅ Education should teach "how to learn" - not just fixed knowledge

> 📌 **Exam Tip**: Automation won't replace all jobs - it will change them. Humans + Robots = Better outcomes

---

## 5. Record and Play (Introduction)

### Why Recording is Important:
- Recording user steps + playing them back = foundation of RPA success
- Without recording, RPA would be just another complex scripting tool
- Makes automation accessible to non-programmers

### What Recording Does:
1. Captures mouse clicks, keyboard typing, UI interactions
2. Converts actions into a "Recording Sequence" in UiPath Studio
3. Robot replays these steps automatically

### Two Recording Modes:

| Mode | When to Use | Limitations |
|------|-------------|-------------|
| **Automatic Recording** | Record many steps in one go | Cannot record: hotkeys, right-click, double-click, modifier keys (Ctrl/Alt) |
| **Manual Recording** | Record one step at a time with full control | Slower, but can record ALL actions including hotkeys, right-click, hover |

### Shortcut Keys During Recording:
| Key | Action |
|-----|--------|
| **F2** | Pause recording for 3 seconds (countdown shown on screen) |
| **Right-click** | Exit recording |
| **Esc** | Exit recording; press Esc again to save the recording |

---

## 6. Downloading and Installing UiPath Studio (Step-by-Step)

### Step-by-Step Installation Guide:

**Step 1: Visit Community Edition Page**
- Open browser → Go to: `https://www.uipath.com/community`
- Click **"Get Community Edition"**

**Step 2: Register Account**
- Fill required fields:
  - First Name*
  - Last Name*
  - Email* (use correct email - needed for activation)
  - Twitter User (optional)
- Click **"REQUEST COMMUNITY EDITION"**

**Step 3: Download Installer**
- Check your email for download link
- OR click **"download it here"** on the confirmation page
- Download file: `UiPathStudioSetup.exe`

**Step 4: Run Installer**
- Double-click downloaded `.exe` file
- Wait for installation to complete
- Click **"Start Free"** on welcome screen

**Step 5: Activate Software**
- Enter same email used for registration
- Click **"Activate"** (online activation only for Community Edition)
- Wait for success message → Close window

**Step 6: Pin for Easy Access (Optional but Recommended)**
- Right-click UiPath icon → "Pin to taskbar"
- Avoids searching for `UiPath.exe` every time

✅ **Installation Complete!** UiPath Studio is ready to use.

> 🔐 **Important**: 
> - Use same email for registration AND activation
> - Community Edition requires online activation (no offline option)
> - Auto-updates enabled by default

---

## 7. Learning UiPath Studio

### Types of Projects in UiPath:

| Project Type | Best Used For | How to Start |
|-------------|--------------|-------------|
| **Sequence** | Simple, linear tasks; easy debugging | Start tab → Blank → Add Sequence from toolbox |
| **Flowchart** | Complex processes with decisions/branches | New Project menu → "Flowchart - Simple Process" |
| **Assistant** | Attended/Front Office Robots (human-triggered) | New Project menu → "Assistant - Agent Process Improvement" |
| **State Machine** | Large projects with finite states triggered by conditions | New Project menu → "Process - Transaction Business Process" |

> 📌 **Note**: From DESIGN tab → New menu, you only see: Sequence, Flowchart, State Machine (not Assistant)

---

### UiPath Studio User Interface (12 Key Panels):

```
┌─────────────────────────────────────┐
│ 1. Ribbon (Top)                     │
│ 2. Quick Access Toolbar             │
├─────────────┬───────────────────────┤
│ 8. Import   │ 4. Properties Panel   │
│ 9. Activity │ 5. Outline Panel      │
│10. Library  │ 6. Arguments Panel    │
│11. Project  │ 7. Variables Panel    │
├─────────────┴───────────────────────┤
│ 3. Designer Panel (Main Workspace)  │
├─────────────────────────────────────┤
│12. Output Panel (Bottom)            │
└─────────────────────────────────────┘
```

#### Panel Functions (Simple Explanation):

| Panel | Location | Purpose |
|-------|----------|---------|
| **1. Ribbon** | Top | 4 tabs: START (new/open projects), DESIGN (create workflows), EXECUTE (run/debug), SETUP (publish/extensions) |
| **2. Quick Access Toolbar** | Above Ribbon | Shortcuts to Save, Run; customizable |
| **3. Designer Panel** | Center | Main workspace to build workflows by dragging activities |
| **4. Properties Panel** | Right | View/edit properties of selected activity |
| **5. Outline Panel** | Right (below Properties) | High-level view of workflow structure; drill down for details |
| **6. Arguments Panel** | Right (below Outline) | Create arguments to pass data between workflows (In/Out/In/Out/Property) |
| **7. Variables Panel** | Bottom-left | Create/manage variables (String, Int32, Boolean, etc.); set Scope |
| **8. Import Panel** | Left (below Activity) | Import namespaces/packages |
| **9. Activity Panel** | Left | Search and drag activities into Designer |
| **10. Library Panel** | Left (below Import) | Reuse automation snippets across projects |
| **11. Project Panel** | Left (below Library) | View project files; open in Windows Explorer |
| **12. Output Panel** | Bottom | Shows logs, errors, warnings, debug output during execution |

---

### Variables vs Arguments (Key Difference):

| Feature | Variables | Arguments |
|---------|-----------|-----------|
| **Purpose** | Store data within a workflow | Pass data BETWEEN workflows |
| **Scope** | Limited to workflow/sequence where created | Can cross workflow boundaries |
| **Direction Property** | Not applicable | In / Out / In/Out / Property |
| **When to Use** | Temporary data storage in one workflow | Sharing data between parent/child workflows |

> 💡 **Tip**: Rename a variable in Variables panel → it auto-updates everywhere it's used in that workflow

---

## 8. Task Recorder (Detailed)

### Four Types of Recording:

| Recorder | Best For | Selector Type | Output Structure | Special Notes |
|----------|----------|---------------|-----------------|--------------|
| **Basic** | Single-window apps, simple actions | Full Selector (all attributes) | Activities directly in Sequence | No Attach Window container |
| **Desktop** | Desktop apps, multiple actions/windows | Partial Selector (hierarchical) | Activities inside **Attach Window** | Attach Window ensures correct window focus |
| **Web** | Web browsers (Chrome, Firefox, etc.) | Partial Selector | Activities inside **Attach Browser** | Requires browser extension installed first |
| **Citrix** | Remote desktop, virtual machines, Citrix | Image/Text-based selectors | Click Image, Click Text, Type activities | Only manual (single-step) recording; no auto-record |

---

### Installing Browser Extension (Required for Web Recording):
1. In UiPath Studio → Click **SETUP** tab in Ribbon
2. Click **"Setup Extensions"**
3. Choose your browser (Chrome/Firefox/Edge)
4. Click to install extension
5. Restart browser if prompted

---

### Recording Panel Options (After Starting Recording):

| Button | Purpose | Example Use |
|--------|---------|-------------|
| **Start App / Open Browser** | Launch application or open URL | Start Notepad; Open `gmail.com` |
| **Click** | Click/tap on UI element | Click "Submit" button; Check checkbox |
| **Type** | Type text into field | Enter username in login box |
| **Copy / Paste** | Copy text or paste clipboard content | Copy value from one field to another |
| **Element / Text / Image** | Target specific UI element types | Click image icon; Get text from label |

#### Type Activity Settings:
- **Empty field checkbox**: Clears existing text before typing new value
- **Press Enter after typing**: Automatically adds Enter keypress
- **Text property**: Can use literal text `"Hello"` or variable `userName`

#### Click Activity Settings:
- **ClickType property**: Single / Double / Right-click (change in Properties panel)

---

### Advanced UI Interactions: Input & Output Methods

#### Input Methods (How robot sends keystrokes):
| Method | Speed | Works in Background? | Best For |
|--------|-------|---------------------|----------|
| **Default** | Slowest | ❌ No | Testing; when other methods fail |
| **Simulate** | Fastest | ✅ Yes | Preferred method for most cases |
| **Window Message** | Fast | ✅ Yes | When Simulate doesn't work; types lowercase only |

> 🔧 **How to change**: Select Type activity → Properties panel → Check "Simulate" or "SendWindowMessages"

#### Output Methods (How robot extracts text):
| Method | Accuracy | Speed | Extracts Position? | Works in Citrix? | Extracts Hidden Text? |
|--------|----------|-------|-------------------|------------------|----------------------|
| **Native** | 100% | Fast (8/10) | ✅ Yes | ❌ No | ❌ No |
| **Full Text** | 100% | Fastest (10/10) | ❌ No | ❌ No | ✅ Yes |
| **OCR** | ~98% | Slow (3/10) | ✅ Yes | ✅ Yes | ❌ No |

> 🔧 **How to change**: When indicating element → Scraping window appears → Choose method

#### OCR Engines Available:
- **Microsoft OCR (MODI)**: Better for large text areas; multiple languages by default
- **Google OCR (Tesseract)**: Better for small text; supports color inversion; filter allowed characters
- **Abbyy OCR**: Advanced (handwriting, complex layouts); install via Manage Packages (Ctrl+P)

> 💡 **Pro Tip**: If OCR struggles with small text, increase **Scale** property (1.5 or 2.0) in OCR activity

---

## 9. Step-by-Step Examples Using the Recorder

### Example 1: Emptying Trash Folder in Gmail (Web Recording)

#### Process Flow (6 Steps):
```
1. Open Browser → 2. Go to gmail.com → 3. Sign In → 
4. Locate Trash Folder → 5. Click Empty Trash → 6. Confirm
```

#### Detailed Recording Steps:

**Preparation**: Open browser and navigate to `gmail.com` (keep open)

**Step 1: Start Web Recorder**
- In UiPath Studio → Click **Recording** icon (DESIGN tab)
- Select **Web** recording
- Recording panel appears with "Open Browser" option

**Step 2: Record Open Browser**
- Click **Open Browser** in recording panel
- Highlight your already-open browser window → Click
- (This records the browser reference; doesn't reopen it)

**Step 3: Record Navigation to Gmail**
- When prompted for URL → Type `gmail.com` or `https://gmail.com`
- Click **OK**

**Step 4: Record Sign In**
- Click **Record** button in recording panel
- In Gmail page:
  - Click "Email or Phone" field → Type your email in UiPath prompt → Press Enter
  - Click "NEXT" button (auto-recorded)
  - Click password field → Type password in prompt → Click "NEXT"
  - (For real projects: Check "Type password" checkbox for security)

**Step 5: Locate Trash Folder**
- Click Gmail search box → Type `in:trash` in UiPath prompt → Press Enter
- Click "Search" button (auto-recorded)
- Wait for Trash folder results to appear

**Step 6: Empty Trash**
- Hover over "Empty Trash now" link → Click when highlighted
- If "Indicate Anchor" dialog appears:
  - Click "Indicate Anchor"
  - Click adjacent stable element (e.g., "Cancel" button) to help robot locate target
- When confirmation dialog appears → Click "OK"

**Step 7: Finish Recording**
- Press **Esc** key → Click **"Save & Exit"**
- In Designer panel: Rename sequence to `emptying_trash_folder` (for clarity)
- Press **F5** to test → Robot repeats all steps automatically

✅ **Result**: Gmail trash folder is emptied automatically!

---

### Example 2: Emptying Recycle Bin (Desktop Recording)

#### Process Flow (6 Steps):
```
1. Go to Desktop → 2. Open Recycle Bin → 3. Click Manage Tab → 
4. Click Empty Recycle Bin → 5. Confirm Yes → 6. Close Folder
```

#### Detailed Recording Steps:

**Step 1: Start Desktop Recorder**
- In UiPath Studio → Click **Recording** icon
- Select **Desktop** recording
- Recording panel appears

**Step 2: Record Each Action**
1. **Go to Desktop**: Press `Windows + D` (not recorded, but not needed - next step attaches to desktop)
2. **Open Recycle Bin**:
   - Click Recycle Bin icon on desktop
   - ⚠️ **Important**: Recording captures "Select" but NOT the Enter key
   - After recording: Manually add **Send Hotkey** activity below "Select item" step
     - Search "Send Hotkey" in Activities panel
     - Drag below the Select step
     - Set Key = "Enter"
3. **Click Manage Tab**: Click "Manage" tab in Recycle Bin window (auto-recorded)
4. **Click Empty Recycle Bin**: Click the button (auto-recorded)
5. **Confirm Deletion**: When dialog appears → Click "Yes" (auto-recorded)
6. **Close Folder**: Click close (X) button
   - If "Indicate Anchor" appears → Click adjacent element (e.g., Minimize button) to help locate

**Step 3: Finish & Test**
- Press **Esc** → Click **"Save & Exit"**
- Press **F5** to run → Robot empties Recycle Bin automatically

#### Troubleshooting Tip:
If Recycle Bin opens with single-click instead of double-click:
1. Find "Click Recycle Bin" activity in sequence
2. Select it → Go to Properties panel
3. Change **ClickType** from "Single" to "Double"

✅ **Result**: Recycle Bin is emptied without manual intervention!





# UNIT – III: Sequence, Flowchart, and Control Flow
## Exam Preparation Notes (Simple & Detailed)

---

## 1. Sequencing the Workflow

### What is a Sequence?
- A **Sequence** is a group of logical steps where each step represents an action or work
- Used for processes that happen **one after another** in linear order
- Among UiPath project types, Sequences are the **smallest and simplest**

### UiPath Project Types:
| Project Type | Best Used For |
|-------------|--------------|
| **Sequence** | Simple, linear automation tasks |
| **Flowchart** | Complex processes with decisions |
| **User Events** | Front office robots |
| **State Machines** | Complex business processes |

### How to Build a Simple Sequence (Step-by-Step):
1. Open UiPath Studio → Click **Blank** → Give project a meaningful name
2. Search for **"Sequence"** in Activities panel → Drag and drop into Designer
3. Double-click the Sequence to add steps inside
4. Add **Input Dialog** activity:
   - Search "Input Dialog" in Activities panel
   - Drag it inside the Sequence
   - In Label property, write your question (e.g., "What is your name?")
5. Add **Message Box** activity:
   - Search "Message Box" → Drag inside Sequence
   - This will display the user's answer
6. Create a **String variable** (e.g., "userName"):
   - Go to Variables panel
   - Click Create Variable
   - Name: userName, Type: String
7. Connect Input Dialog to variable:
   - Select Input Dialog → Go to Properties panel
   - Find **Result** property → Click dotted icon → Select your variable name
8. Connect variable to Message Box:
   - Select Message Box → In Text property, type your variable name
9. Set Sequence as Start:
   - Right-click Sequence → Select "Set as Start node"
10. Click **Run** or press **F5** to see result

---

## 2. Activities

### What is an Activity?
- An **activity** is the smallest unit of action in UiPath
- Each activity performs one specific action
- When activities combine, they form a complete process/automation

### Using Activities:
- All activities are in the **Activities panel** (left side of Designer)
- Search for any activity using the search bar (e.g., search "browser" to see all browser-related activities)
- Use activities by:
  - **Drag and drop** method, OR
  - **Double-click** method

### Using Activities with Workflows:
**Why use workflows?**
- Big projects with hundreds of activities are hard to debug
- Solution: Break project into smaller modules called **workflows**
- Each workflow can be tested separately → easier to find bugs
- Benefits: Better code quality, maintainability, reliability, readability

### How to Extract Activities as Workflow (Step-by-Step):
1. Create your activities inside a Flowchart or Sequence
2. Select the activities you want to group
3. Right-click on Designer panel → Choose **"Extract as Workflow"**
4. A window pops up → Give meaningful name → Click **Create**
5. UiPath automatically creates an **"Invoke [WorkflowName]"** activity in main Designer
6. Double-click the Invoke activity to see which workflow it calls
7. When you Run, it executes the extracted workflow

---

## 3. Control Flow, Various Types of Loops, and Decision Making

### What is Control Flow?
- Control flow = the **order** in which actions are performed in automation
- UiPath provides many activities for decision-making and looping

### Types of Control Flow Activities:
| Activity | Purpose |
|----------|---------|
| **Assign** | Give a value to a variable |
| **Delay** | Pause automation for specified time |
| **Break** | Stop a loop at a particular point |
| **While** | Repeat while condition is true |
| **Do While** | Execute once, then repeat while condition is true |
| **For Each** | Go through each item in a collection |
| **If** | Make decision: true or false |
| **Switch** | Choose from multiple options |

---

### The Assign Activity
- Used to **assign a value to a variable**
- Examples of use:
  - Increment variable value in a loop
  - Store result of calculation (sum, difference, etc.)
- Properties:
  - **To**: Variable name that will receive the value
  - **Value**: The value or expression to assign

---

### The Delay Activity
- Used to **pause/slow down** automation for a defined time
- Format: `hh:mm:ss` (hours:minutes:seconds)
- Useful when waiting for an application to open or load

#### Example: Delay Between Two Messages (Step-by-Step):
1. Create new Flowchart
2. Add **Write Line** activity → Connect to Start node
3. In Write Line Text property, type: `"Hey, what is your name?"`
4. Add **Delay** activity → Connect to Write Line
5. Select Delay → In Properties panel, set Duration: `00:00:50` (50 seconds)
6. Add another **Write Line** → Connect to Delay
7. In second Write Line Text, type: `"My name is Andrew Ng"`
8. Click **Run** → Output panel shows first message, waits 50 seconds, then shows second message

---

### The Break Activity
- Used to **stop/exit a loop** at a particular point
- **Only works inside For Each activity**
- Useful when you want to stop looping after finding what you need

#### Example: Break After First Iteration (Step-by-Step):
1. Add **Sequence** to Designer panel
2. Add **For Each** activity inside Sequence
3. Create two variables:
   - `item` (type: generic, auto-created by For Each)
   - `x` (type: Array of Int32)
4. Set default value for `x`: `{1, 2, 3, 4, 5}`
5. Inside For Each body, add **Break** activity
6. Also inside For Each, add **Write Line** activity
7. In Write Line Text, type: `item.ToString`
8. Click **Run** → Only first element displays because Break stops loop after first iteration

---

### What are Loops?
- Loops repeat a part of workflow for different cases or when criteria are met
- **Important**: Always include an **exit point**, otherwise loop runs infinitely!
- Loop types in UiPath: While, Do While, For Each

---

### The While Activity
- Executes statements **while a condition is true**
- Checks condition **first**, then executes if true
- Exits loop when condition becomes false
- Useful for iterating through arrays

#### Example: Count from 5 to 50 by 5s (Step-by-Step):
1. Create Blank project → Add **Sequence**
2. Create integer variable `y`, set default value: `5`
3. Add **While** activity to Sequence
4. In While Condition field, set: `y <= 50`
5. Inside While body, add **Assign** activity:
   - To: `y`
   - Value: `y + 5`
6. Add **Write Line** inside While body
7. In Write Line Text, type: `y.ToString`
8. Click **Run** → Output shows: 5, 10, 15, 20, 25, 30, 35, 40, 45, 50

---

### The Do While Activity
- **Difference from While**: Executes statement **first**, then checks condition
- Guarantees at least one execution even if condition is false initially
- Exits loop when condition becomes false

#### Example: Generate Multiples of 2 Less Than 20 (Step-by-Step):
1. Add **Sequence** to Designer
2. Add **Do While** activity
3. Inside Do While body, add **Assign** activity:
   - Create integer variable `z`, default value: `2`
   - In Assign: To = `z`, Value = `z + 2`
4. Add **Write Line** inside body → Text: `z.ToString`
5. In Do While Condition field, set: `z < 20`
6. Click **Run** → Output: 4, 6, 8, 10, 12, 14, 16, 18

---

### The For Each Activity
- Iterates through **each element** in a collection/list, one at a time
- Executes all actions inside its body for each element
- Perfect for processing arrays or lists

#### Example: Display Even Numbers from Array (Step-by-Step):
1. Start Blank project → Add **Sequence**
2. Add **For Each** activity inside Sequence
3. Create variable `y` (type: Array of Int32)
4. Set default value: `{2, 4, 6, 8, 10, 12, 14, 16, 18, 20}`
5. Inside For Each body, add **Write Line** activity
6. In Write Line Text, type: `item.ToString` (item is auto-generated variable)
7. Click **Run** → Each number displays one by one

---

### Decision Making Activities

#### The If Activity
- Has **two conditions**: True or False
- If statement is true → executes Then block
- If statement is false → executes Else block

#### Example: Check if Sum of Two Numbers < 6 (Step-by-Step):
1. Add **Flowchart** from Activities panel
2. Add two **Input Dialog** activities
3. Create two integer variables: `x` and `y`
4. In each Input Dialog Properties:
   - Set Label/Title as needed
   - In Result property, assign respective variable (x or y)
5. Add **If** activity to Flowchart
6. In If Condition field, type: `x + y < 6`
7. Inside If's Then block: Add Write Line with Text: `"True"`
8. Inside If's Else block: Add Write Line with Text: `"False"`
9. Click **Run** → If sum < 6, shows "True"; otherwise shows "False"

---

#### The Switch Activity
- Used to **choose from multiple options**
- By default takes integer argument, but can change TypeArgument in Properties
- Very useful for categorizing data

#### Example: Check if Number is Odd or Even (Step-by-Step):
1. Add **Sequence** activity
2. Add **Input Dialog** inside Sequence
3. Create integer variable `k`
4. In Input Dialog Result property, assign variable `k`
5. Add **Switch** activity below Input Dialog
6. In Switch Expression field, type: `k Mod 2` (checks remainder when divided by 2)
7. In Switch **Default** case:
   - Add Write Line
   - Text: `k.ToString + " is an even number"`
8. Create **Case 1** (for remainder = 1, meaning odd):
   - Add Write Line
   - Text: `k.ToString + " is an odd number"`
9. Click **Run** → Shows whether entered number is odd or even

---

## 4. Step-by-Step Examples Using Sequence and Flowchart

### When to Use Sequence vs Flowchart?
| Feature | Sequence | Flowchart |
|---------|----------|-----------|
| Best for | Linear, step-by-step tasks | Complex processes with decisions |
| Structure | Activities execute in order | Activities can branch, loop, reverse |
| Reusability | Can be nested in Flowcharts | Can contain Sequences, reusable across projects |
| Decision making | Limited | Multiple branching options (true/false branches) |

---

### How to Use a Sequence (Simple Example)
**Goal**: Ask user name → Display it back

#### Steps:
1. Drag **Flowchart** onto Designer panel
2. Drag **Sequence** inside Flowchart → Connect to Start node
3. Double-click Sequence to enter it
4. Add **Input Dialog** activity:
   - In Label property, write: "What is your name?"
5. Add **Message Box** activity
6. Create String variable (e.g., `userName`)
7. In Input Dialog Result property → Select `userName` variable
8. In Message Box Text property → Type `userName`
9. Press **F5** to Run → Dialog asks name → Message box displays entered name

**Key Point**: Sequence executes activities in the order you place them. You can add as many activities as needed.

---

### How to Use a Flowchart with Sequences (Email Example)
**Goal**: Understand grouping Sequences inside Flowcharts (conceptual, not full email code)

#### Steps:
1. On main Flowchart, drag two **Flowchart** activities
2. Rename them: `SendMail` and `Message`
3. For each Flowchart:
   - Double-click to enter
   - Drag **Sequence** inside
   - Right-click Sequence → "Set as Start node"
4. Inside **Message Flowchart's Sequence**:
   - Add four **Input Dialog** activities for: name, message, sender, receiver
   - (No need to set properties for this lesson)
5. Inside **SendMail Flowchart's Sequence**:
   - This is where email activities would go (covered in later chapter)
6. Return to main Flowchart:
   - Connect Message Flowchart to Start node
   - Connect SendMail Flowchart to Message Flowchart
7. Click **Run** to visualize flow

**Key Point**: Group related activities in Sequences → Group related Sequences in Flowcharts → Each represents a task → Easy to test separately.

> 📝 **Note**: To use email activities, install UiPath.Mail.Activities package via Manage Packages (Ctrl+P) → Search "mail"

---

## 5. Step-by-Step Examples Using Sequence and Control Flow

### Example: Count Names Starting with Letter 'A'
**Goal**: Given array of names, count how many start with 'A' and display result

#### Steps:
1. Drag **Flowchart** from Activities panel
2. Drag **Sequence** inside Flowchart → Right-click → "Set as Start node"
3. Double-click Sequence:
   - Create variable `names` (type: Array of String)
   - In Default section, initialize: `{"John", "Sam", "Andrew", "Anita"}`
   - Create integer variable `Count` (type: Int32, default: 0) to store result
4. Add **For Each** activity inside Sequence:
   - In Expression field, type: `names` (the array to iterate)
5. Inside For Each body, add **If** activity:
   - In Condition field, type: `item.ToString.StartsWith("A")`
   - This checks if current name starts with "A"
6. Inside If's **Then** block:
   - Add **Assign** activity
   - To: `Count`
   - Value: `Count + 1` (increment counter)
7. After For Each loop, add **Message Box** activity:
   - In Text property, type: `Count.ToString`
   - (Convert Int32 to String using .ToString method)
8. Click **Run** or press **F5** → Result: `2` (Andrew and Anita start with A)

---

## 6. Data Manipulation (Introduction)

### What is Data Manipulation?
- Process of **changing data**: adding, removing, or updating it
- Before manipulating data, understand:
  - Variables and their scope
  - Collections (arrays, lists)
  - Arguments (for passing data between workflows)
  - Data tables (tabular data structure)

### Why Learn Data Manipulation?
- Store and retrieve data efficiently
- Work with files (CSV, Excel)
- Scrape data from web
- Build dynamic automations

---

## 7. Variables and Scope

### What is Memory?
- Memory has millions of **cells**, each storing data as 0s and 1s
- Each cell has a **unique address** for access
- Data is split into smaller binary forms when stored

### What is a Variable?
- A **name given to a block of memory** to hold data
- You can declare any meaningful name for a variable
- **Best practice**: Use descriptive names (e.g., `userName`, `flightNumber`) not ambiguous ones (e.g., `temp`, `data`)

### Variable Data Types in UiPath:
| Type | Content it Holds | Example |
|------|-----------------|---------|
| **Integer** | Whole numbers | 5, 100, -3 |
| **String** | Text of any kind | "Hello", "User123" |
| **Boolean** | True or False | True, False |
| **Generic** | Anything | Any data type |

### How to Declare a Variable:
1. Go to **Variables panel** (bottom-left in Designer)
2. Click **Create Variable**
3. Fill:
   - Name: Meaningful name (e.g., `userName`)
   - Type: Select from dropdown (String, Int32, etc.)
   - Default: Optional initial value
   - Scope: Where variable is accessible (see below)

### What is Scope?
- **Scope** = region where variable is available/effective
- Choose scope based on need; **limit it as much as possible**
- Security tip: Don't set scope to fullest unnecessarily (risk of accidental access/modification)

#### Example: Using Variable in Message Box (Step-by-Step):
1. In Variables panel, create variable:
   - Name: `name`, Type: String, Default: `"Hello World"`
2. Search **"Message Box"** in Activities panel → Drag to Flowchart
3. Right-click Message Box → "Set as Start node"
4. Double-click Message Box → In Text property, type variable name: `name`
5. Click **Run** → Dialog pops up showing "Hello World"

---

## 8. Collections

### Types of Variables:
| Category | Description | Examples |
|----------|-------------|----------|
| **Scalar** | Holds single data point | Integer, String, Boolean |
| **Collections** | Holds one or more data points of same type | Array, List, Dictionary |
| **Tables** | Tabular structure with rows and columns | Data Table |

### What is a Collection?
- Can store **multiple values**, but all must be **same data type**
- **Array**: Fixed-size collection (cannot add/remove after creation)
- **Exception**: Array of Objects can store different data types

### Using Arrays (Step-by-Step Example):
**Goal**: Initialize integer array → Display each element

1. Drag **Flowchart** → Add **Sequence** inside → Set as Start node
2. Create variable `arr` (type: Array of Int32)
3. In Default section, initialize: `{1, 2, 3, 4, 5}`
4. Add **For Each** activity inside Sequence
5. In For Each Expression field, type: `arr`
6. Inside For Each body, add **Message Box**
7. In Message Box Text, type: `item.ToString`
   - (Convert item to String because Message Box expects String)
8. Click **Run** → Each value pops up one by one

---

## 9. Arguments (Purpose and Use)

### What is an Argument?
- Similar to variable but with **larger scope**
- Used to **pass values between different workflows**
- Created in **Arguments panel** of Designer

### Why Use Arguments?
- Break big projects into smaller, testable workflows
- Workflows need to exchange data → Arguments enable this communication

### Argument Directions:
| Direction | Purpose |
|-----------|---------|
| **In** | Receive value from another workflow |
| **Out** | Send value to another workflow |
| **In/Out** | Both send and receive |
| **Property** | Not currently used |

### How to Create an Argument:
1. Open **Arguments panel** (next to Variables panel)
2. Click **Create Argument**
3. Fill:
   - Name: Meaningful name
   - Direction: In/Out/In/Out
   - Type: Data type (String, Int32, etc.)
   - Default: Optional initial value

---

## 10. Data Table Usage with Examples

### What is a Data Table?
- **Tabular data structure** with rows and columns
- Example structure:
```
| Student Name | Roll Number | Class |
|--------------|-------------|-------|
| Andrew Jose  | 1           | 3     |
| Jorge Martinez| 2          | 3     |
| Stephen Cripps| 3          | 2     |
```

### Uses of Data Table:
- Build tables dynamically
- Store tabular data in memory
- **Data scraping**: Extract web data into tabular format
- Read/write Excel/CSV files

---

### Building a Data Table (Step-by-Step):
**Goal**: Create data table with Student Name, Roll No, Class → Display rows

1. Create Blank project → Add **Flowchart** → Add **Sequence** → Set as Start
2. Double-click Sequence → Add **Build Data Table** activity
3. Click **Data Table** button → Popup appears
4. Remove auto-generated columns (click Remove Column icon)
5. Add three columns using **+** icon:
   - Column 1: Name = `Name`, Type = String
   - Column 2: Name = `Roll_No`, Type = Int32
   - Column 3: Name = `Class`, Type = String
6. Click **OK** → Add sample row values in the table
7. Create variable `MyDataTable` (type: DataTable)
8. In Build Data Table Output property → Assign `MyDataTable`
9. Add **For Each Row** activity inside Sequence:
   - In Expression field, type: `MyDataTable`
10. Inside For Each Row body, add **Message Box**:
    - In Text, type:
    ```
    row("Name").ToString + "." + row("Roll_No").ToString + "." + row("Class").ToString
    ```
    - (`row` is auto-variable holding current row data)
11. Click **Run** → Each row displays in message box

> 💡 **Note**: "For Each" iterates collections; "For Each Row" iterates data table rows

---

### Building Data Table Using Data Scraping (Dynamic)
**Goal**: Extract book names from Amazon website into data table

#### Steps:
1. Add **Flowchart** → Add **Sequence** → Set as Start
2. Double-click Sequence → Add **Open Browser** activity
3. In Open Browser URL field, paste Amazon search URL for books
4. Click **Data Scraping** icon (top-left of UiPath Studio)
5. Wizard opens → Click **Next**
6. Pointer appears → Click on **first book name** on webpage
7. Wizard asks for second similar element → Click **second book name**
8. Specify column name for extracted data (e.g., "BookName") → Click **Next**
9. List of extracted names appears in preview window
10. To extract more data (e.g., price):
    - Click **Extract correlated data**
    - Repeat steps 6-8 for price element
11. To finish: Click **Finish** (or extract next page if needed)
12. If extracting multiple pages:
    - Click **Yes** when asked for next page link
    - Point to "Next Page" button on website
13. Data scraping generates data table variable (e.g., `ExtractedDataTable`)
14. Change scope of `ExtractedDataTable` to **Flowchart** (so it's accessible)
15. Add **Output Data Table** activity:
    - In Data Table property: `ExtractedDataTable`
16. Create String variable `result` to receive output
17. In Output Data Table Text property: assign `result` variable
18. Add **Message Box** → In Text property: type `result`
19. Connect all activities in order
20. Click **Run** → Message box displays scraped data

---

## 11. Clipboard Management

### What is Clipboard Management?
- Managing clipboard activities: getting text, copying selected text, etc.

### Example: Get Text from Clipboard Using Notepad (Step-by-Step):
**Goal**: Write in Notepad → Copy text → Extract from clipboard → Display

1. Add **Flowchart** to Designer
2. Click **Recording** icon (top of Studio) → Select **Desktop** → Click Record
3. Click **Notepad** to open it
4. Click Notepad text area → Type your text
   - Check "Empty field" option to clear existing data first
   - Press Enter after typing
5. Click **Edit** menu in Notepad:
   - When asked for anchor element, select **Format** button (relative element)
   - From dropdown, select **Select All**
6. Click **Edit** menu again:
   - Indicate anchor again → Select **Copy** from dropdown
   - Text is now in clipboard
7. Stop recording → Double-click generated Recording Sequence
8. Scroll down → Drag **Copy Selected Text** activity inside Sequence
9. Create String variable (e.g., `clipboardText`)
10. In Copy Selected Text Output property → Assign `clipboardText`
11. Add **Message Box** activity → In Text property: type `clipboardText`
12. Click **Run** → Message box displays copied text from clipboard

---

## 12. File Operations with Step-by-Step Examples

### Common Excel File Methods:
| Method | Purpose |
|--------|---------|
| **Read Cell** | Read value from specific cell |
| **Write Cell** | Write value to specific cell |
| **Read Range** | Read values from specified range (or entire sheet) |
| **Write Range** | Write collection of rows to Excel (as data table) |
| **Append Range** | Add data to end of existing Excel file |

> 💡 **Best Practice**: Always use **Excel Application Scope** activity when working with Excel activities

---

### Read Cell (Step-by-Step):
**Goal**: Read value from cell B3 in Excel file

1. Add **Flowchart** → Add **Excel Application Scope** → Connect to Start
2. Double-click Excel Application Scope → Specify Excel file path
3. Inside scope, add **Read Cell** activity
4. In Read Cell properties:
   - Cell: `B3` (the cell to read)
   - Create String variable `Result`
   - In Output property: assign `Result` variable
5. Add **Message Box** inside scope → In Text: type `Result`
6. Press **F5** → Message box shows value from cell B3

---

### Write Cell (Step-by-Step):
**Goal**: Write a value to specific Excel cell

1. Add **Flowchart** → Add **Excel Application Scope** → Connect to Start
2. Double-click scope → Specify Excel file path
3. Inside scope, add **Write Cell** activity
4. In Write Cell properties:
   - Range: Cell address (e.g., `C5`)
   - Value: Text or variable to write
5. Press **F5** → Open Excel file to see new value in specified cell

---

### Read Range (Step-by-Step):
**Goal**: Read entire Excel sheet or specified range into data table

1. Add **Flowchart** → Add **Excel Application Scope** → Connect to Start
2. Inside scope, add **Read Range** activity
3. Read Range produces a data table → Create DataTable variable (e.g., `excelData`)
4. In Read Range Output property: assign `excelData`
5. Add **Output Data Table** activity inside scope:
   - Data Table property: `excelData`
   - Create String variable `Result`
   - Text property: assign `Result`
6. Add **Message Box** → In Text: type `Result`
7. Press **F5** → Message box displays Excel data as string

---

### Write Range (Step-by-Step):
**Goal**: Build data table → Write all rows to Excel file

1. Add **Build Data Table** activity:
   - Double-click → Remove auto columns → Add your columns using **+**
   - Example: Column "Name" (String), Column "Roll" (Int32)
   - Add sample row values
2. Create DataTable variable (e.g., `myTable`)
3. In Build Data Table Output property: assign `myTable`
4. Add **Excel Application Scope** → Specify target Excel file path
5. Inside scope, add **Write Range** activity
6. In Write Range properties:
   - Data Table: `myTable`
   - Range: Leave empty (writes from start) or specify (e.g., `A1`)
7. Click **Run** → Excel file now contains your data table rows

---

### Append Range (Step-by-Step):
**Goal**: Read data from one Excel file → Append to another Excel file

1. Add **Flowchart** → Add **Excel Application Scope** (for source file) → Connect to Start
2. Inside scope, add **Read Range** activity:
   - Create DataTable variable `sourceData`
   - In Output property: assign `sourceData`
3. Add another **Excel Application Scope** (for target file) or reuse same scope
4. Inside scope, add **Append Range** activity:
   - Specify target Excel file path
   - In Data Table property: assign `sourceData` (from Read Range)
5. Press **F5** → Open target Excel file → See appended data at end

---

## 13. CSV/Excel to Data Table and Vice Versa (Step-by-Step)

### Part A: Read Excel/CSV → Create Data Table

#### Steps:
1. Add **Flowchart** → Add **Excel Application Scope** → Specify file path
2. Inside scope, add **Read Range** activity:
   - Creates data table from Excel/CSV
   - Create DataTable variable (e.g., `fileData`)
   - In Output property: assign `fileData`
3. Add **Output Data Table** activity:
   - Data Table property: `fileData`
   - Create String variable `result`
   - Text property: assign `result`
4. Add **Message Box** → In Text: type `result`
5. Press **F5** → Message box shows file data as string

---

### Part B: Create Data Table → Write to Excel/CSV

#### Steps:
1. Add **Build Data Table** activity:
   - Double-click → Configure columns (name, type)
   - Add sample row values
2. Create DataTable variable (e.g., `newTable`)
3. In Build Data Table Output property: assign `newTable`
4. Add **Excel Application Scope** → Specify target file path
5. Inside scope, add **Write Range** activity:
   - Data Table property: `newTable`
   - Range: Leave empty or specify start cell
6. Click **Run** → Target file now contains your data table

---


# UNIT – IV: Handling Events & Controls
## Exam Preparation Notes (Simple & Detailed)

---

## 1. Taking Control of the Controls (Introduction)

### What is this chapter about?
- After learning workflows and variables, we now learn **how to interact with UI controls**
- Controls = buttons, textboxes, menus, windows in applications
- We need to: **find controls**, **wait for them**, **act on them** (click, type, read)

### Why is this important?
- RPA = extracting info from UI + taking actions on UI
- Sometimes normal methods fail → need advanced techniques like OCR
- This chapter teaches selectors, UiExplorer, events, recorders, and screen scraping

---

## 2. Finding and Attaching Windows

### What is Attach Window Activity?
- Used to **attach to an already opened window** (like Notepad, Excel, browser)
- Auto-generated when using Basic/Desktop recorder
- Helps robot "focus" on correct window before performing actions

### Step-by-Step: Attach Window with Notepad (Simple Steps)
1. Create Blank project → Give meaningful name
2. Drag **Flowchart** to Designer panel
3. Drag **Click** activity → Right-click → "Set as Start node"
4. Double-click Click → Click "Indicate on screen" → Click Notepad icon
5. Drag **Attach Window** activity → Connect to Click activity
6. Double-click Attach Window → Click "Click Window on Screen" → Click Notepad window
7. Drag **Type Into** activity INSIDE Attach Window
8. Double-click Type Into → Click "Indicate element inside window" → Click where to type in Notepad
9. In Text property of Type Into: type your message (e.g., "Hello from Robot")
10. Click **Run** → Notepad opens, robot types your text

> 💡 **Key Point**: Attach Window ensures actions happen in correct window, even if multiple windows are open

---

## 3. Finding the UI Control

### What are "Find Control" Activities?
- Activities that help robot **locate UI elements** on screen
- Used when selector is unreliable or element changes frequently

### Types of Find Control Activities:

| Activity | Purpose | When to Use |
|----------|---------|-------------|
| **Anchor Base** | Find element by looking at nearby element | When selector is unreliable |
| **Element Exists** | Check if UI element is present | When element may/may not appear |
| **Element Scope** | Attach to one element, perform multiple actions | When many actions on same element |
| **Find Children** | Find all child elements of a parent | When processing lists/tables |
| **Find Element** | Find specific UI element, wait for it | When element loads slowly |
| **Find Relative Element** | Find element using nearby fixed element | When selector is weak |
| **Get Ancestor** | Get parent/ancestor of an element | When you need container info |
| **Indicate on Screen** | Select element at runtime | For dynamic/flexible selection |

---

### Anchor Base (Detailed Steps)
**Use when**: You can't rely on selector alone

1. Drag **Flowchart** → Drag **Anchor Base** → Connect to Start
2. Double-click Anchor Base → You see two slots:
   - **Anchor**: Drag "Find Element" here (the nearby stable element)
   - **Action**: Drag "Type Into" here (what you want to do)
3. For Anchor: Indicate the stable nearby element (e.g., a label)
4. For Action: Indicate the target element + type your text
5. Robot finds target by looking relative to anchor → performs action

---

### Element Exists (Detailed Steps)
**Use when**: You're not sure if element will appear

1. Drag **Element Exists** from Activities panel
2. Double-click → Click "Indicate on screen" → Click the UI element
3. Create Boolean variable (e.g., `isFound`)
4. In Properties panel → Exists property → Assign `isFound` variable
5. Use **If activity**: Condition = `isFound = True`
   - Then: Do action if element exists
   - Else: Handle missing element case

---

### Element Scope (Detailed Steps)
**Use when**: Multiple actions on same element

1. Drag **Element Scope** → Double-click → Indicate the UI element
2. Inside "Do" sequence: Add all activities for that element
   - Example: Type Into → Click → Get Text → All on same element
3. Robot attaches once → performs all actions → detaches

---

### Find Children (Detailed Steps)
**Use when**: You need all items inside a container (like list items)

1. Drag **Find Children** → Double-click → Indicate parent element
2. Create variable: Type = `IEnumerable<UiElement>`
3. In "Children" property → Assign your variable
4. Add **For Each** activity → Expression = your children variable
5. Inside loop: Process each child element

---

## 4. Techniques for Waiting for a Control

### Why wait for controls?
- Applications take time to load
- Robot may act too fast → element not ready → error
- Waiting ensures element is stable before action

### Three Waiting Techniques:

#### A. Wait Element Vanish
**Use when**: You want to wait until element DISAPPEARS

**Steps**:
1. Drag **Wait Element Vanish** → Set as Start node
2. Double-click → Click "Indicate on screen" → Click element that should vanish
3. Robot waits until that element is gone → then continues
4. Optional: Set timeout in Properties (default = 30 seconds)

#### B. Wait Image Vanish
**Use when**: You want to wait until an IMAGE disappears

**Steps**: Same as above, but indicate an image instead of element
- Useful for loading spinners, splash screens

#### C. Wait Attribute
**Use when**: You want to wait until element's attribute equals specific text

**Steps**:
1. Drag **Wait Attribute** → Set as Start node
2. Double-click → Fill three fields:
   - **Element**: Indicate the UI element
   - **Attribute**: Name of attribute (e.g., "Enabled", "Visible")
   - **Value**: Expected value (e.g., "True", "Ready")
3. Robot waits until attribute matches value → then continues

---

## 5. Act on Controls: Mouse and Keyboard Activities

### Mouse Activities (3 types)

#### A. Click Activity
**Use when**: You need to click a button, link, or any clickable element

**Steps**:
1. Search "mouse" in Activities panel → Drag **Click** activity
2. Right-click → "Set as Start node"
3. Double-click → Click "Indicate on screen" → Click target element
4. Optional: In Properties, set ClickType (Single, Double, Right)
5. Click **Run** → Robot clicks the element

#### B. Double-Click Activity
**Use when**: You need to double-click (like opening a file)

**Steps**: Same as Click, but use **Double Click** activity instead

#### C. Hover Activity
**Use when**: You need to hover over element (to show tooltip/menu)

**Steps**:
1. Drag **Hover** activity → Set as Start node
2. Double-click → Indicate element to hover over
3. Robot moves mouse over element → waits briefly → continues

---

### Keyboard Activities (3 types)

#### A. Send Hotkey
**Use when**: You need to press keyboard shortcuts (Ctrl+C, Enter, Arrow keys)

**Steps**:
1. Search "keyboard" → Drag **Send Hotkey** → Set as Start
2. Double-click → Indicate target window/page
3. In Properties:
   - Check boxes for modifier keys (Ctrl, Alt, Shift)
   - Select main key from dropdown (Enter, Down, Esc, etc.)
4. Click **Run** → Robot sends the key combination

#### B. Type Into
**Use when**: You need to type text into a textbox/field

**Steps**:
1. Drag **Type Into** → Double-click → Indicate where to type
2. In Text property: Type your text or variable name
3. Optional: Click "+" icon to add special keys (Enter, Tab, etc.)
4. Click **Run** → Robot types your text

#### C. Type Secure Text
**Use when**: You need to type passwords/sensitive data securely

**Steps**:
1. Create variable: Type = `SecureString`
2. Drag **Type Secure Text** → Double-click → Indicate target field
3. In SecureText property: Assign your SecureString variable
4. Robot types text without showing it in logs/screens

> 🔐 **Note**: In enterprise, use **Get Credential** activity with Orchestrator for secure password handling

---

## 6. Working with UiExplorer

### What is UiExplorer?
- Advanced tool to **view and edit selectors**
- Used when normal selector fails (e.g., window title changes)
- Shows all attributes of a UI element (title, class, app, etc.)

### When to use UiExplorer?
**Example Problem**: 
- Robot types in Notepad titled "Untitled - Notepad"
- You save file as "test.txt" → title changes to "test - Notepad"
- Robot fails next time because selector still looks for "Untitled"

### Step-by-Step: Fix Selector with UiExplorer
1. Double-click the failing activity (e.g., Type Into)
2. In Properties panel → Expand "Target" → Find "Selector" property
3. Click dotted icon next to Selector → Click "Open in UiExplorer"
4. UiExplorer window opens → Shows selector code like:
   ```
   <wnd app='notepad.exe' title='Untitled - Notepad' ... />
   ```
5. Find the changing attribute (e.g., `title='Untitled - Notepad'`)
6. Edit it to be flexible:
   - Option A: Use wildcard: `title='* - Notepad'` (* matches any text)
   - Option B: Use new title: `title='test - Notepad'`
7. Click "Validate" → If green checkmark, click "Apply"
8. Robot now works with updated selector

### Wildcard Characters in Selectors:
| Symbol | Meaning | Example |
|--------|---------|---------|
| `*` (asterisk) | Replaces any number of characters | `title='Report*'` matches "Report1", "Report_Final" |
| `?` (question mark) | Replaces exactly one character | `file='doc?.pdf'` matches "doc1.pdf", "docA.pdf" |

> 💡 **Pro Tip**: Use "Attach to live element" in selector window to auto-fix changing attributes

---

## 7. Handling Events

### What is an Event?
- An event = something that happens (click, keypress, image change)
- Robot can **listen for events** → trigger actions when event occurs

### Types of Events:

#### A. Element Triggering Events
**1. Click Trigger**
- Fires when specified element is clicked

**Steps**:
1. Drag **Monitor Events** activity → Double-click
2. Inside Monitor Events: Drag **Click Trigger**
3. In Click Trigger: Indicate the element to watch
4. In "Event Handler" section: Add activities to run when clicked
   - Example: Message Box with "Button was clicked!"
5. Robot monitors → when element clicked → runs handler

**2. Key Press Trigger**
- Fires when keys are pressed on specified element

**Steps**: Same as Click Trigger, but use **Key Press Trigger**
- Specify which key(s) to watch for (e.g., Enter, Ctrl+S)

#### B. Image Triggering Events
**Click Image Trigger**
- Fires when a specific IMAGE is clicked

**Steps**:
1. Inside Monitor Events: Drag **Click Image Trigger**
2. Indicate the image to watch (screenshot of button/icon)
3. Add handler activities → Run when image is clicked

#### C. System Triggering Events
**1. Hotkey Trigger**
- Fires when special keyboard shortcut is pressed anywhere

**Steps**:
1. Inside Monitor Events: Drag **Hotkey Trigger**
2. Specify key combination (e.g., Ctrl+Alt+R)
3. Add handler → Runs when hotkey pressed

**2. Mouse Trigger**
- Fires when mouse button is pressed

**Steps**:
1. Inside Monitor Events: Drag **Mouse Trigger**
2. Choose button: Left / Middle / Right
3. Add handler → Runs on mouse click

**3. System Trigger**
- Fires on ANY keyboard/mouse event (most flexible)

**Steps**:
1. Inside Monitor Events: Drag **System Trigger**
2. In "Trigger Input": Choose event type (KeyDown, MouseUp, etc.)
3. Add handler → Runs on specified system event

> ⚠️ **Important**: Always use **Monitor Events** as container for any trigger activity

---

## 8. Revisit Recorder

### Four Types of Recording in UiPath:

| Recorder | Best For | Selector Type | Output Structure |
|----------|----------|---------------|-----------------|
| **Basic** | Single-window apps, simple actions | Full Selector | Activities directly in Sequence |
| **Desktop** | Desktop apps, multiple actions | Partial Selector | Activities inside Attach Window |
| **Web** | Web browsers (Chrome, Firefox, etc.) | Partial Selector | Activities inside Attach Browser |
| **Citrix** | Remote desktop, virtual apps | Image/Text based | Click Image, Click Text activities |

---

### Basic Recording (Step-by-Step)
**Use for**: Simple, single-window tasks

1. Click "Recording" icon → Choose "Basic"
2. Perform actions in target app (click, type, etc.)
3. Press Esc → Click "Save and Exit"
4. Result: Sequence with activities + full selectors
5. Connect to Start → Run

> 📌 Full Selector = Contains ALL attributes to identify element (very specific)

---

### Desktop Recording (Step-by-Step)
**Use for**: Desktop apps with multiple windows/actions

1. Click "Recording" → Choose "Desktop"
2. Perform actions across windows
3. Press Esc → Save and Exit
4. Result: Activities nested inside **Attach Window** container
5. Partial selectors = hierarchical (parent→child structure)

> 📌 Partial Selector = More flexible, uses relative positioning

---

### Web Recording (Step-by-Step)
**Use for**: Automating web browsers

**Pre-requisite**: Install UiPath browser extension
- Click "Setup" icon → "Setup Extensions" → Choose browser → Install

**Recording Steps**:
1. Open target website in browser
2. Click "Recording" → Choose "Web"
3. Perform web actions (search, click, login, etc.)
4. Press Esc → Save and Exit
5. Result: Activities inside **Attach Browser** container
6. Connect to Start → Ensure browser is on correct page before running

---

### Citrix Recording (Step-by-Step)
**Use for**: Remote desktop, virtual machines, Citrix environments

**Why special?**: In Citrix, robot sees only images (not UI elements)

**Available Activities**:
- Click Image, Click Text, Type, Select & Copy, Screen Scraping, Element, Text, Image

**Steps**:
1. Click "Recording" → Choose "Citrix"
2. Perform actions in remote session
3. Robot records based on:
   - **Image position** (where you clicked)
   - **Text recognition** (what text you typed)
4. Press Esc → Save and Exit
5. Result: Activities using image/text-based selectors

> ⚠️ Citrix automation is less reliable → Always test thoroughly

---

### Data Scraping (Bonus: Extract Web Data)
**Use when**: You need to extract lists/tables from websites

**Step-by-Step: Scrape Amazon Book Names**
1. Open Amazon → Search for books
2. In UiPath: Click "Data Scraping" icon (top-left)
3. Wizard opens → Click "Next"
4. Pointer appears → Click FIRST book name on page
5. Wizard asks for SECOND similar element → Click second book name
6. Configure column: Name = "BookName" → Click "Next"
7. Preview shows extracted names → If satisfied, click "Finish"
8. Optional: Click "Extract correlated data" to add more columns (price, author)
9. Optional: If multiple pages → Click "Yes" → Indicate "Next Page" button
10. Result: Auto-generated sequence + DataTable variable with scraped data
11. Use "Output Data Table" or "For Each Row" to process results

---

## 9. Screen Scraping

### What is Screen Scraping?
- Method to **extract text** from documents, websites, PDFs
- Three methods available: Full Text, Native, OCR

### Comparison of Three Methods:

| Feature | Full Text | Native | OCR |
|---------|-----------|--------|-----|
| **Speed** | 10/10 (Fastest) | 8/10 | 3/10 (Slowest) |
| **Accuracy** | 100% | 100% | ~98% |
| **Background Execution** | ✅ Yes | ❌ No | ❌ No |
| **Extract Text Position** | ❌ No | ✅ Yes | ✅ Yes |
| **Extract Hidden Text** | ✅ Yes | ❌ No | ❌ No |
| **Works in Citrix** | ❌ No | ❌ No | ✅ Yes |

---

### Step-by-Step: Use Screen Scraping Wizard
1. Open target app/website with text to extract
2. In UiPath: Click "Screen Scraping" icon
3. Indicate area containing text
4. Wizard tries methods in order:
   - First: Automatic (tries best method)
   - If fails: Try Full Text → Native → OCR
5. When text appears in preview → Click "Finish"
6. Result: Extracted text stored in variable (usually String or DataTable)

> 💡 **Tip**: If Automatic fails, manually select method that works for your content

---

## 10. When to Use OCR

### What is OCR?
- **Optical Character Recognition** = Technology to read text from images/scanned docs
- Used when normal methods (Get Text, Type Into) FAIL

### When to choose OCR?
✅ Use OCR when:
- Text is in an **image** (screenshot, photo)
- Document is **scanned PDF** (not selectable text)
- Application is **Citrix/remote** (only images visible)
- Text is in **non-standard font** or handwritten
- Normal activities return empty/wrong text

❌ Don't use OCR when:
- Text is already selectable (use Get Text instead)
- You need 100% accuracy (OCR is ~98%)
- Speed is critical (OCR is slow)

---

## 11. Types of OCR Available

### Two Built-in OCR Engines:

#### A. Microsoft OCR (MODI)
**Advantages**:
- Multiple languages supported by default
- Better for **large text areas**
- Good for standard documents

**Limitations**:
- Less accurate on small/complex text
- Requires Windows components

#### B. Google OCR (Tesseract)
**Advantages**:
- Better for **small text areas**
- Supports color inversion (dark mode)
- Can filter allowed characters
- Better for non-Latin scripts

**Limitations**:
- Slower on large areas
- May need language packs installed

### Third-Party OCR: Abbyy
- More advanced (handwriting, complex layouts)
- Search "OCR" in Activities panel → If not found:
  - Press Ctrl+P → Search "UiPath.Core.Activities" → Install package

---

## 12. How to Use OCR (Step-by-Step)

### Example: Extract Text from Image
1. Create Blank project → Drag **Flowchart**
2. Search "OCR" → Drag **Get OCR Text** activity → Set as Start
3. Double-click → Click "Indicate on screen"
4. Draw box around text in image (e.g., Google image with text)
5. In "Text" property: Click dotted icon → Create variable (e.g., `extractedText`, type: String)
6. Drag **Message Box** → Connect to Get OCR Text
7. In Message Box Text: Type `extractedText`
8. Optional: In Get OCR Text Properties → Adjust "Scale" (1.0 = normal, 2.0 = zoomed for small text)
9. Click **Run** → Message box shows extracted text

> 🔧 **Pro Tip**: If text is small/blurry, increase Scale to 1.5 or 2.0 for better recognition

---

## 13. Avoiding Typical Failure Points

### Common Problems & Solutions:

#### Problem 1: Selector Fails When App Instance Changes
**Cause**: Selector captures exact title/class, but these change between runs
**Solution**:
- Use wildcards: `title='Report*'` instead of `title='Report_2024'`
- Or: Use "Attach to live element" in selector window

#### Problem 2: Variable Scope Error
**Cause**: Variable created inside Sequence/Loop → not accessible outside
**Solution**:
- When creating variable: In "Scope" dropdown, choose parent container (e.g., Flowchart)
- Or: Move variable creation to higher scope

#### Problem 3: Robot Acts Too Fast (Element Not Ready)
**Cause**: App still loading → element not stable → action fails
**Solution**:
- Add **Delay** activity before action (e.g., `00:00:05` for 5 seconds)
- Or: Use **Element Exists** to check before acting
- Or: Use **Wait Attribute** to wait for "Enabled=True"

#### Problem 4: Element May Not Exist
**Cause**: Optional UI element sometimes missing → robot crashes
**Solution**:
- Wrap action in **Element Exists** + **If** condition
- Example:
  ```
  Element Exists → Output: isFound (Boolean)
  If isFound = True → Then: Perform action
  Else → Log "Element not found, skipping"
  ```

#### Problem 5: Try/Catch for Unexpected Errors
**Use when**: Action might fail for unknown reasons
**Steps**:
1. Drag **Try Catch** activity
2. Inside "Try" block: Put suspicious activities
3. Inside "Catch" block: Add error handling (Log Message, Retry, etc.)
4. Robot tries actions → If error → Jumps to Catch → Handles gracefully

#### Problem 6: Forgetting .ToString() Method
**Cause**: Message Box expects String, but variable is Integer/Boolean
**Solution**:
- Always convert non-String variables: `myInt.ToString`, `myBool.ToString`
- Example: Message Box Text = `count.ToString` (not just `count`)

---


# UNIT – V: Exception Handling, Debugging, and Logging
## Exam Preparation Notes (Simple & Detailed)

---

## 1. Exception Handling

### What is Exception Handling?
- Exception handling = managing errors when a process/automation fails to execute
- Best practice in UiPath: Use the **Try Catch** activity
- Keeps your robot running smoothly even when unexpected errors occur

### Structure of Try Catch Activity:
A Try Catch block is divided into **4 main parts**:

| Part | Purpose |
|------|---------|
| **Try Block** | Place your main/suspicious activities here (what you want to run) |
| **Catch Block** | Runs ONLY if an error occurs in Try block. Handles the exception |
| **Finally Block** | Runs ALWAYS, whether error occurred or not. Used for cleanup/completion messages |
| **Exception Type** | Select which error to catch (e.g., `System.Exception` for general errors) |

### Step-by-Step: Build a Try Catch Block
1. Create Blank project → Drag **Flowchart** → Search **"Try Catch"** in Activities panel
2. Drag Try Catch into Flowchart → Right-click → **Set as Start node**
3. Double-click Try Catch → You'll see **Try**, **Catches**, and **Finally** sections
4. **Inside Try**: Drag your main activities (e.g., Write Line, Click, etc.)
5. **Inside Catches**: 
   - Click **"Add new catch"** → Select exception type (usually `System.Exception`)
   - Drag error-handling activity here (e.g., Message Box)
   - In Message Box Text: type `exception.ToString` to display the actual error message
6. **Inside Finally**: Drag completion activity (e.g., Message Box with `"Process completed"`)
7. Click **Run** → If Try works → Finally runs. If Try fails → Catch runs → Then Finally runs

> 💡 **Key Point**: Finally block guarantees execution, making it perfect for closing apps, logging, or showing completion status.

---

## 2. Common Exceptions and Ways to Handle Them

### How to Handle Common Errors:

| Exception | Cause | Simple Fix |
|-----------|-------|------------|
| **Unavailability of UI Element** | Web page loads slowly or elements change dynamically | Edit selector using wildcards (`*` or `?`) OR use **"Attach to live element"** |
| **Runtime Exceptions** | Unexpected error during execution | Wrap workflow in **Try Catch** → Provide alternative steps in Catch block |
| **Object reference not set to an instance of an object** | Variable missing a default value | Go to Variables panel → Add a **Default value** (e.g., `""` for String, `0` for Integer) |
| **Index was outside bounds of array / Index out of range** | Trying to access array element that doesn't exist | Check array size before accessing → Use valid index numbers only |
| **Image not found in provided timeout** | Screen resolution/theme changed, image doesn't match | Use **Indicate Anchor** to locate nearby stable element OR adjust timeout |
| **Click Generic error** (Cannot use UI CONTROL API...) | Environment doesn't support Simulate Click or Send Window Messages | Uncheck **Simulate Click** OR **SendWindowMessages** in activity Properties |

### Quick Fix Workflow for UI Errors:
1. Identify failing activity
2. Check selector → Replace changing attributes with `*` (matches any text) or `?` (matches one character)
3. If still failing → Use **Anchor Base** or **Indicate Anchor**
4. Wrap in **Try Catch** for safety

---

## 3. Logging and Taking Screenshots

### What is Logging in UiPath?
- Logging = recording workflow execution details for tracking, debugging, and auditing
- UiPath uses **multi-process architecture**: Each workflow runs in separate executor managed by UI Robot. If one fails, others continue.

### Types of Logging:
| Type | Description |
|------|-------------|
| **Client Logging** | Logs stored locally on your machine. Configured via `NLog.config` file |
| **Server Logging** | Logs automatically sent to UiPath Server (if configured) |

### How to Access & Configure Logs:
- **View logs**: In UiPath Studio → Click **EXECUTE** → Click **Open Logs**
- **Default log folder**: `%LocalAppData%\UiPath\Logs`
- **Log sources**: 
  - Execution logging (workflow steps)
  - Studio logging (Studio actions)
  - Robot logging (Robot actions)
- **Enable detailed auto-logging**: 
  1. Open `UiRobot.exe.config` file
  2. Find `<Switches>` section
  3. Change `Log` value from `1` to `2`
  4. Save → Restart Robot

### Activities for Logging:
| Activity | Use Case |
|----------|----------|
| **Log Message** | Logs info/warning/error to Output panel & log files (choose log level: Info, Warn, Error) |
| **Write Line** | Writes text to Output panel only (good for quick debugging) |

### Taking Screenshots:
- Press **`Ctrl + PrtScrn`** anytime during execution to capture current screen
- Useful for error reporting & debugging visual issues

---

## 4. Debugging Techniques

### What is Debugging?
- Testing workflow step-by-step to find & fix errors before full execution
- UiPath provides tools in the **EXECUTE** ribbon menu

### Four Main Debugging Techniques:

#### A. Setting Breakpoints
**Use when**: You want execution to stop at a specific point
**Steps**:
1. Click on any activity → Press `F9` OR click breakpoint icon in EXECUTE tab
2. Red circle appears → Activity is now a breakpoint
3. Run workflow → Execution pauses JUST BEFORE the breakpoint
4. Use **Step Into** (executes current activity) or **Step Over** (skips to next)
5. Click **Continue** to resume full execution

#### B. Slow Step
**Use when**: You want to watch each activity run slowly to spot timing issues
**Steps**:
1. Select activity → Click **Slow Step** in EXECUTE tab
2. Execution speed reduces for that step
3. Watch Output panel to track progress step-by-step

#### C. Highlighting
**Use when**: You want to visually see which activity is currently running
**Steps**:
1. In EXECUTE tab → Open **Options** menu
2. Enable **Highlighting**
3. During execution, active activity glows/highlights on Designer panel
4. Helps track exact workflow path

#### D. Break Activity
**Use when**: You want to manually stop execution at a specific point during runtime
**Steps**:
1. Drag **Break** activity into workflow at desired location
2. When execution reaches it → Robot pauses
3. Click **Continue** to resume OR **Stop** to end execution completely

> 💡 **Exam Tip**: Breakpoints = stop before activity. Slow Step = slow down execution. Highlighting = visual tracking. Break = manual pause/stop.

---

## 5. Collecting Crash Dumps

### What are Crash Dumps?
- Crash dump = file containing system info when UiPath Studio crashes
- Helps developers diagnose why crash happened
- Two types:
  - **Full Dump**: Complete crash information (larger file)
  - **Minidump**: Main crash information only (smaller file)

### Identify Crashed Process:
- Dialog box appears showing crash details
- Common crashing processes: `UiStudio.exe`, `UiExplorer.exe`, `UiLauncher.exe`, or target application

### Step-by-Step: Enable Crash Dumps
1. Download enable file from official links:
   - Full dump: `EnableFullDump.reg`
   - Mini dump: `EnableMiniDump.reg`
2. Double-click downloaded `.reg` file
3. Click **Yes** to confirm (Administrator rights required)
4. If crash occurs → Go to `%TEMP%` folder
5. Look for `.dmp` file (e.g., `UiExplorer.exe.8537.dmp`)
6. Share this file for troubleshooting

### Step-by-Step: Disable Crash Dumps
1. Download `DisableDump.reg` from official link
2. Double-click file → Click **Yes** (Admin rights required)
3. Crash dumps will no longer be generated

> ⚠️ **Note**: Always run `.reg` files as Administrator. Dumps are saved in your Windows TEMP folder.

---

## 6. Error Reporting

### How to Report Errors in UiPath?
Depends on your UiPath edition:

#### A. Enterprise Edition Customers
**Steps**:
1. Visit official technical support/contact page
2. Fill out the simple error reporting form with:
   - Your details
   - Error description
   - Steps to reproduce
3. **Upload error file** (logs, crash dumps, screenshots)
4. Click **Submit**
5. UiPath support team will analyze and respond with solution

#### B. Community Edition Customers
- Community Edition is **free** → No direct technical support from UiPath
- **How to get help**:
  1. Visit **UiPath Forum** (`forum.uipath.com`)
  2. Search for your error → Read existing solutions
  3. If not found → Post new question with error details & screenshots
  4. Check **Resources page** for tutorials & troubleshooting guides

> 💡 **Pro Tip**: Always include workflow screenshots, error message text, and log files when asking for help. This speeds up solution finding.
