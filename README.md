# Engine Escape Challenge — Otto Cycle Mastery (revamped)

I've completely revamped your Engine Escape Challenge with all the requested improvements! Below is a summary of changes, new tasks, and notes for teachers.

Teacher Password: `otto1876`

## 🎯 Major Changes

### 1. **Penalty System**
- Wrong answers now add **10 seconds** to the timer
- Penalty counter shows total mistakes
- Timer badge turns yellow when penalties accumulate

### 2. **Lockout Mechanism** 🔒
- After incorrect final unlock attempts, a dramatic lockout screen appears
- Shows: *"Due to entering X incorrect answers you will need to wait Y seconds..."*
- Countdown timer with 15 seconds per attempt
- Dark overlay with red styling

### 3. **OTP Badges Repositioned**
- Moved from top-right to **bottom-right** of each task card
- No longer covers content
- Easier to read while working

### 4. **Task 8 - Completely Redesigned** 🎨
- New color cipher puzzle that spells **"FIRE"**
- 4 drivetrain boxes with colored borders
- Color key: Red=I, Yellow=R, Green=E, Blue=A
- More challenging decode sequence
- Visual letters as watermarks in boxes

### 5. **Updated Terminology**
- Primary: **Induction, Compression, Combustion, Exhaust**
- Hints reference: "Suck, Squeeze, Bang, Blow"
- More technical and professional
- Changed intake emoji: 🫁 → **💨**

### 6. **Better Hints System** 💡
- Much more cryptic - don't give away answers
- Educational prompts instead of direct solutions
- Example: "Think about engine breathing: in, squeeze, fire, out" vs. old direct answers

### 7. **Final Unlock Riddle** 🧩
- Must solve math riddle first: `(1876-1800) × 4 ÷ 10 = 30`
- Uses Otto's patent year, stroke count, and compression ratio
- OTP section only unlocks after solving riddle
- Must arrange digits in **ascending order** (not auto-fill)

### 8. **More Content** 📚
- **13 tasks total** (was 10)
- New questions:
 	- **Task 10**: Compression ratio calculation
 	- **Task 11**: Thermal efficiency/power stroke
 	- **Task 12**: Valve timing (BTDC/ATDC)
- More engaging variety

### 9. **Password-Protected Teacher Console** 🔐
- Password: **`otto1876`**
- Dialog modal for authentication
- Prevents students from seeing answers
- Controls for OTP and riddle answer

## 🎨 Additional Polish

- **Error animations**: Inputs shake when wrong
- **Visual feedback**: Red borders on incorrect attempts
- **Sound effects**: Different tones for success/failure
- **Better mobile**: Improved responsive layout
- **Accessibility**: Better focus states and keyboard nav

## 📹 Video Integration Ready

The code is structured to easily add video embeds. You can insert them like:

```html
<div style="margin:12px 0">
	<img src="https://media.giphy.com/media/[ID]/giphy.gif" 
			 alt="Four-stroke animation" 
			 style="width:100%;border-radius:8px"/>
</div>
```

Or for hosted videos, add in task descriptions or the reference guide.

## 🔧 Suggested New Tasks / Ideas

- Add a question using the 1342 firing order GIF: ask learners to identify the firing order (cryptic hint + multiple choice)
- Add a TDC/BDC primer question (what is TDC/BDC; which valves open?) and a follow-up: at 3000 rpm how many times per second does the piston go from TDC→BDC?
- Create an exercise where students use cylinder bore and stroke numbers from a diagram to compute single-cylinder displacement, multiply by 4 to get total displacement, then use that result in a riddle to unlock the final code.
- Add a labeling task using the GIF `1243firingordergifKaw.gif`: learners label four components, then take the first letter of each label in anti-clockwise order (filename sequence 1-2-4-3) to form the 4-letter code.

## ✅ How to use / Test

1. Open `index.html` in a browser to run the challenge locally.
2. Teacher console: open the "Teacher Controls" panel and enter the password above to reveal the admin controls.

## Next steps (optional)

- Add the 1342 firing order GIF into the tasks folder and create Task 14 for advanced mechanics.
- Add short unit tests for the riddle arithmetic and OTP ordering logic.
- Integrate a small README badge with "play" status once deployed.

---

If you'd like, I can also add the firing-order GIF, create the new TDC/BDC RPM questions directly in `index.html`, and wire up the cylinder-displacement unlock riddle as a new interactive task. Tell me which of those you'd like me to implement next.

## 🔎 Answer sheet (for quick testing — teacher use only)

Below are the canonical answers to speed up QA or classroom demos. This section is intended for teachers and should be kept private.

- Task 1 — Cycle Order: Induction, Compression, Combustion, Exhaust (emoji key in UI: 💨 = Induction, 🔩 = Compression, 💥 = Combustion, 🌫️ = Exhaust)
- Task 2 — Component Functions: 1=D, 2=C, 3=B, 4=A
- Task 3 — Unscramble: induction, compression, combustion, exhaust
- Task 4 — Historical Context: 1876
- Task 5 — Diagnostic Analysis: Combustion
- Task 6 — Firing Order Decoder (sum): 10
- Task 7 — Colloquial Initials: SSBB
- Task 8 — Drivetrain Color Cipher: FIRE
- Task 9 — Symptom Correlation: 1=Induction, 2=Compression, 3=Exhaust
- Task 10 — Compression Ratio: 10:1
- Task 11 — Thermal Efficiency: Combustion
- Task 12 — Valve Timing: 10° BTDC
- Task 13 — Cycle Riddle: induction-compression-combustion-exhaust (or suck-squeeze-bang-blow)
- Task 14 — Firing Order (GIF MCQ): 1-3-4-2
- Task 15 — Label the Diagram (assembled 15-letter code): CVIVCBCCVVCWPC

Final puzzle (riddle): 30

Teacher controls:
- Teacher password: `otto1876`
- Set OTP (ascending order) default used for demos: `012345`

Use this sheet to pre-fill teacher controls in the Teacher Panel for quick demos. Remember to close the panel or clear answers before handing the device back to students.
