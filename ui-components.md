# UI Components Specifications

## Navigation Bar (Bottom)
- Height: 64dp
- Background: White (#FFFFFF)
- Shadow: 0px -2px 4px rgba(0, 0, 0, 0.05)
- Icons: 24px, Primary Blue (#264653)
- Active icon: Primary Green (#2A9D8F)
- Labels: 12px Tajawal Medium

## Status Bar
- Height: 24dp
- Background: Primary Green (#2A9D8F) for main screens
- Text/icons: White (#FFFFFF)

## Buttons
### Primary Button
- Height: 48dp
- Border radius: 8dp
- Background: Primary Green (#2A9D8F)
- Text: White, 16px Tajawal Bold
- Padding: 16dp horizontal

### Secondary Button
- Height: 48dp
- Border radius: 8dp
- Border: 1px Primary Green (#2A9D8F)
- Background: White (#FFFFFF)
- Text: Primary Green (#2A9D8F), 16px Tajawal Bold
- Padding: 16dp horizontal

### Icon Button
- Size: 48dp x 48dp
- Icon size: 24dp
- Border radius: 24dp (circle)
- Background: Light Grey (#EEEEEE) or transparent

## Cards
### Product Card
- Border radius: 12dp
- Background: White (#FFFFFF)
- Shadow: 0px 2px 4px rgba(0, 0, 0, 0.1)
- Padding: 16dp
- Title: 18px Tajawal Bold, Dark Grey (#333333)
- Subtitle: 14px Tajawal Regular, Medium Grey (#666666)
- Image container: 80x80dp, border radius 8dp

### Information Card
- Border radius: 12dp
- Background: Secondary Green (#8ECBC0) at 10% opacity
- Border: 1px Secondary Green (#8ECBC0)
- Padding: 16dp
- Icon: 20px Primary Green (#2A9D8F)
- Text: 14px Tajawal Regular, Dark Grey (#333333)

## Progress Indicators
### Match Percentage Circle
- Size: 64dp x 64dp
- Track thickness: 6dp
- Track color: Light Grey (#EEEEEE)
- Progress color based on percentage:
  - 0-30%: Accent Orange (#E76F51)
  - 31-70%: Accent Yellow (#E9C46A)
  - 71-100%: Accent Green (#4CAF50)
- Percentage text: 18px Tajawal Bold, Dark Grey (#333333)

### Linear Progress
- Height: 8dp
- Border radius: 4dp
- Track color: Light Grey (#EEEEEE)
- Progress color: Primary Green (#2A9D8F)

## Input Fields
### Text Input
- Height: 56dp
- Border radius: 8dp
- Border: 1px Light Grey (#EEEEEE)
- Active border: Primary Green (#2A9D8F)
- Background: White (#FFFFFF)
- Text: 16px Tajawal Regular, Dark Grey (#333333)
- Placeholder: 16px Tajawal Regular, Medium Grey (#666666)
- Label: 14px Tajawal Medium, Medium Grey (#666666)
- Padding: 16dp horizontal, 12dp vertical

### Checkbox
- Size: 24dp x 24dp
- Border radius: 4dp
- Border: 1px Medium Grey (#666666)
- Checked background: Primary Green (#2A9D8F)
- Check icon: White (#FFFFFF)
- Label: 16px Tajawal Regular, Dark Grey (#333333)
- Gap between checkbox and label: 12dp

## Tab Navigation
- Height: 48dp
- Active tab indicator: 2dp line, Primary Green (#2A9D8F)
- Active text: Primary Green (#2A9D8F), 16px Tajawal Bold
- Inactive text: Medium Grey (#666666), 16px Tajawal Regular
- Background: White (#FFFFFF)
- Divider: 1px Light Grey (#EEEEEE)

## Camera Scanner Overlay
- Viewfinder border: White (#FFFFFF)
- Scanning animation: Pulsing green line
- Background overlay: Dark Blue (#264653) at 70% opacity
- Instruction text: White (#FFFFFF), 18px Tajawal Bold
- Cancel button: White (#FFFFFF), 16px Tajawal Regular

## Lists
### List Item
- Height: 72dp (minimum)
- Padding: 16dp
- Divider: 1px Light Grey (#EEEEEE)
- Title: 16px Tajawal Medium, Dark Grey (#333333)
- Subtitle: 14px Tajawal Regular, Medium Grey (#666666)
- Leading icon (optional): 24px
- Trailing icon/action: 24px
- Tap state: Light Grey (#EEEEEE) at 20% opacity

## Alerts and Notifications
### Success Alert
- Border radius: 8dp
- Background: Accent Green (#4CAF50) at 10% opacity
- Border: 1px Accent Green (#4CAF50)
- Icon: 24px Accent Green (#4CAF50) checkmark
- Text: 16px Tajawal Regular, Dark Grey (#333333)
- Padding: 16dp

### Warning Alert
- Border radius: 8dp
- Background: Accent Yellow (#E9C46A) at 10% opacity
- Border: 1px Accent Yellow (#E9C46A)
- Icon: 24px Accent Yellow (#E9C46A) exclamation
- Text: 16px Tajawal Regular, Dark Grey (#333333)
- Padding: 16dp

### Error Alert
- Border radius: 8dp
- Background: Accent Orange (#E76F51) at 10% opacity
- Border: 1px Accent Orange (#E76F51)
- Icon: 24px Accent Orange (#E76F51) X icon
- Text: 16px Tajawal Regular, Dark Grey (#333333)
- Padding: 16dp

## Toggle and Switches
### Toggle
- Track size: 50dp x 30dp
- Thumb size: 26dp diameter
- Track radius: 15dp
- Off state: Medium Grey (#666666) track, White (#FFFFFF) thumb
- On state: Primary Green (#2A9D8F) track, White (#FFFFFF) thumb

### Radio Button
- Size: 24dp x 24dp
- Outer circle: 24dp diameter, 1px Medium Grey (#666666) border
- Inner circle (selected): 12dp diameter, Primary Green (#2A9D8F)
- Label: 16px Tajawal Regular, Dark Grey (#333333)
- Gap between radio and label: 12dp

## Specific Components

### Product Match Indicator
- Container: 120dp x 64dp
- Match circle: 64dp diameter
- Percentage text: 18px Tajawal Bold
- Label text: 12px Tajawal Medium
- Color coding:
  - High match (71-100%): Accent Green (#4CAF50)
  - Medium match (31-70%): Accent Yellow (#E9C46A)
  - Low match (0-30%): Accent Orange (#E76F51)

### Halal Badge
- Size: 64dp x 32dp
- Border radius: 16dp
- Verified: Accent Green (#4CAF50) background, White text
- Questionable: Accent Yellow (#E9C46A) background, Dark Grey text
- Non-Halal: Accent Orange (#E76F51) background, White text
- Text: 14px Tajawal Bold

### Allergen Tag
- Height: 28dp
- Border radius: 14dp
- Padding: 8dp horizontal
- Background: Accent Yellow (#E9C46A)
- Text: 12px Tajawal Bold, Dark Grey (#333333)
- Icon: 16px allergen symbol

### Sustainability Rating
- Rating indicator: 5 leaf icons
- Active leaf: Primary Green (#2A9D8F)
- Inactive leaf: Light Grey (#EEEEEE)
- Size: 24dp per leaf
- Label: 14px Tajawal Medium, Dark Grey (#333333)