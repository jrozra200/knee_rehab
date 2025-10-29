# 8-Week Patellar Tendon Rehab Planner

A daily checkbox planner for 8-week patellar tendinopathy rehabilitation with upper body and core work on non-HSR days. All data is stored locally in your browser with no tracking.

**Live App**: https://jrozra200.github.io/knee_rehab/

## Features

- **8-week structured rehab plan** following evidence-based patellar tendinopathy protocols
- **Daily task checklists** for Heavy Slow Resistance (HSR) training, upper body/core work, and mobility
- **Progressive loading** from weeks 1-8 with gradual return-to-play preparation
- **Pain tracking** with peak pain during exercise and next-day pain monitoring
- **VISA-P score tracking** for each week to monitor progress
- **Local autosave** - all progress stored in browser localStorage
- **Export/Import** your progress as JSON for backup or device transfer
- **Print-friendly** layout for physical planning
- **Customizable start date** to align with your rehab timeline

## How to Use

### Getting Started

1. Open `index.html` in a web browser
2. Set your rehabilitation start date using the date picker at the top
3. Click on any day to expand and view the daily plan
4. Check off tasks as you complete them
5. Record your pain levels and notes for each session

### Key Guidelines

**Pain Rule**: Keep pain ≤3/10 during exercise, and ensure symptoms return to baseline within 24 hours. If not, reduce load/volume or repeat a prior day.

**Isometric Holds**: Use for pain relief - 5×45-60s Spanish squat or ~60° leg extension hold at ~70% effort.

### Navigation

- **Expand All / Collapse All**: Quick view controls
- **Reset**: Clear all saved checkboxes and notes (requires confirmation)
- **Export**: Download your progress as JSON
- **Import**: Restore from a previously exported JSON file
- **Print**: Print the entire plan

## Rehabilitation Structure

### Weeks 1-2: Foundation
- HSR training 3×/week (Mon, Wed, Fri)
- Cross-training + upper body on Tue/Thu
- Light mobility work on Saturday
- Complete rest on Sunday

### Weeks 3-4: Plyometric Preparation
- Continue HSR 3×/week
- Introduce plyometric drills (pogo hops, A-skips, line hops)
- Begin run-walk protocols in week 4

### Weeks 5-6: Return to Running
- HSR maintained 3×/week
- Running progression from 2'/1' intervals to continuous 20-30 min
- Increased plyometric and change-of-direction work
- Limited sports-specific practice introduced

### Weeks 7-8: Strength & Return-to-Play
- Heavy strength focus in week 7
- Power/taper work in week 8
- Progressive scrimmage and practice
- Return-to-play testing in final weekend

## Technical Details

This is a static, client-side HTML page with no server dependencies. All functionality is implemented in vanilla JavaScript with no external frameworks.

### Data Storage

- Stored in browser `localStorage` under a key based on your selected start date
- Each start date maintains separate progress data
- Export creates a JSON file you can save and import later

### Privacy

No data leaves your browser. There is no tracking, analytics, or external communication. All data remains 100% local.

## Browser Compatibility

Works in all modern browsers that support:
- ES6 JavaScript
- localStorage API
- HTML5 form elements (date input, number input)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Medical Disclaimer

This rehabilitation planner is for informational purposes only. Always consult with a qualified healthcare professional before starting any rehabilitation program. If pain exceeds guidelines or does not improve, seek professional medical advice.
