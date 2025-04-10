# Figma Implementation Guide

This guide provides step-by-step instructions for implementing the Sustainable Shopping Guide design system in Figma.

## 1. Setting Up Color Styles

1. Open your Figma file
2. Go to the Assets panel (left sidebar)
3. Click on the + icon next to Colors
4. Create the following color styles:

### Primary Colors
- `Primary/Green`: #2A9D8F
- `Primary/Blue`: #264653

### Secondary Colors
- `Secondary/Green`: #8ECBC0
- `Secondary/Blue`: #507D8C

### Accent Colors
- `Accent/Orange`: #E76F51
- `Accent/Yellow`: #E9C46A
- `Accent/Green`: #4CAF50

### Neutral Colors
- `Neutral/Dark`: #333333
- `Neutral/Medium`: #666666
- `Neutral/Light`: #EEEEEE
- `Neutral/White`: #FFFFFF

## 2. Setting Up Text Styles

1. Create a text layer
2. Set the font to Tajawal or Cairo as appropriate
3. Set the size and weight
4. From the Properties panel, click on the four dots next to Text
5. Click the + icon
6. Name your text style using the format: `[Font]/[Type]/[Size]`

Create the following text styles:

### Cairo (Headings)
- `Cairo/H1/Bold`: Cairo, 24px, Bold
- `Cairo/H2/Bold`: Cairo, 20px, Bold
- `Cairo/H3/Bold`: Cairo, 18px, Bold

### Tajawal (Body Text)
- `Tajawal/Body/Regular`: Tajawal, 16px, Regular
- `Tajawal/Body/Medium`: Tajawal, 16px, Medium
- `Tajawal/Body/Bold`: Tajawal, 16px, Bold
- `Tajawal/Caption/Regular`: Tajawal, 14px, Regular
- `Tajawal/Caption/Medium`: Tajawal, 14px, Medium
- `Tajawal/Small/Regular`: Tajawal, 12px, Regular

## 3. Setting Up RTL Text Direction

1. Select any text layer
2. In the Text properties panel, set "Text direction" to "Right to Left"
3. Ensure text alignment is set to "Right aligned"
4. Save this as part of your text styles

## 4. Creating Component Library

### 4.1 Buttons

#### Primary Button
1. Create a new frame (48px height)
2. Draw a rectangle (fill: Primary Green, border radius: 8px)
3. Add a text layer (color: white, font: Tajawal Bold 16px, RTL, right-aligned)
4. Add 16px horizontal padding
5. Select all layers and click "Create Component"
6. Name it "Button/Primary/Default"

#### Secondary Button
1. Create a new frame (48px height)
2. Draw a rectangle (fill: White, stroke: 1px Primary Green, border radius: 8px)
3. Add a text layer (color: Primary Green, font: Tajawal Bold 16px, RTL, right-aligned)
4. Add 16px horizontal padding
5. Select all layers and click "Create Component"
6. Name it "Button/Secondary/Default"

#### Icon Button
1. Create a 48px x 48px frame
2. Draw a circle (48px diameter, fill: Light Grey or transparent)
3. Add an icon (24px, centered)
4. Select all layers and click "Create Component"
5. Name it "Button/Icon/Default"

### 4.2 Create Component Variants

1. Select the Primary Button component
2. In the right sidebar, click "+" under Variants
3. Create variants for:
   - State: Default, Hover, Pressed, Disabled
   - Icon Position: None, Left, Right (for RTL layout, "Left" is on the left of the text)
4. Adjust each variant with appropriate styling
5. Repeat for Secondary and Icon buttons

## 5. Card Components

### Product Card
1. Create a new frame (width: 100%, height: auto)
2. Draw a rectangle (fill: White, border radius: 12px, shadow: 0px 2px 4px rgba(0, 0, 0, 0.1))
3. Add internal padding of 16px
4. Add subcomponents:
   - Product image container (80x80dp, border radius 8dp)
   - Title text (18px Tajawal Bold, Dark Grey, RTL, right-aligned)
   - Subtitle text (14px Tajawal Regular, Medium Grey, RTL, right-aligned)
   - Match percentage indicator (optional)
5. Select all layers and click "Create Component"
6. Name it "Card/Product/Default"

### Information Card
1. Create a new frame (width: 100%, height: auto)
2. Draw a rectangle (fill: Secondary Green at 10% opacity, border: 1px Secondary Green, border radius: 12px)
3. Add internal padding of 16px
4. Add icon (20px Primary Green) at the right side
5. Add text (14px Tajawal Regular, Dark Grey, RTL, right-aligned)
6. Select all layers and click "Create Component"
7. Name it "Card/Information/Default"

## 6. Input Components

### Text Input
1. Create a new frame (height: 56dp, width: 100%)
2. Draw a rectangle (fill: White, border: 1px Light Grey, border radius: 8dp)
3. Add a text layer for label (14px Tajawal Medium, Medium Grey, RTL, right-aligned)
4. Add a text layer for input text (16px Tajawal Regular, Dark Grey, RTL, right-aligned)
5. Add padding: 16dp horizontal, 12dp vertical
6. Select all layers and click "Create Component"
7. Create variants for states: Default, Focus, Filled, Error, Disabled

### Checkbox
1. Create a 24dp x 24dp frame
2. Draw a square (24dp, border: 1px Medium Grey, border radius: 4dp)
3. Create a check icon (white) for the selected state
4. Create variants for states: Unchecked, Checked
5. For the checked variant, set the square fill to Primary Green
6. Select all layers and click "Create Component"
7. Name it "Checkbox/Default"

## 7. Scanner Components

### Camera Viewfinder
1. Create a new frame (full screen width, aspect ratio 4:3)
2. Draw a rectangle with a transparent center and semi-transparent overlay around the edges
3. Add a white border around the transparent center
4. Add scan instruction text above ("امسح الباركود", white, 18px Tajawal Bold, centered)
5. Add a horizontal green line for the scanning animation
6. Select all layers and click "Create Component"
7. Name it "Scanner/Viewfinder"

### Match Percentage Circle
1. Create a 64dp x 64dp frame
2. Draw a circle (64dp diameter) with Light Grey fill for the track
3. Draw an arc for the progress part (color varies based on percentage)
4. Add text for percentage (18px Tajawal Bold, Dark Grey, centered)
5. Add label text below (12px Tajawal Regular, Medium Grey, centered)
6. Create variants for different percentage ranges: 0-30%, 31-70%, 71-100%
7. Select all layers and click "Create Component"
8. Name it "Indicator/Match/Default"

## 8. Navigation Components

### Bottom Navigation Bar
1. Create a new frame (height: 64dp, full screen width)
2. Draw a rectangle (fill: White, shadow: 0px -2px 4px rgba(0, 0, 0, 0.05))
3. Create 4 navigation items with:
   - Icon (24px)
   - Label (12px Tajawal Medium)
4. Space items evenly
5. Create variants for each active state (Scanner, History, Education, Profile)
6. Select all layers and click "Create Component"
7. Name it "Navigation/Bottom"

### Tab Navigation
1. Create a new frame (height: 48dp, full screen width)
2. Draw a rectangle (fill: White, border-bottom: 1px Light Grey)
3. Add text for each tab ("الاستدامة", "الحلال", "الحساسية")
4. Add an active indicator line (2dp height, Primary Green)
5. Create variants for each active tab
6. Select all layers and click "Create Component"
7. Name it "Navigation/Tabs"

## 9. Setting Up Auto Layout for RTL

For components that contain multiple elements in a horizontal arrangement:
1. Select the container frame
2. In the Design panel, click the Auto Layout icon
3. Set "Direction" to "Right to Left"
4. Set appropriate spacing between items
5. Use constraints to ensure proper RTL layout

## 10. Creating Screen Templates

### Onboarding Screen
1. Create a frame with mobile device dimensions
2. Add status bar
3. Add content container with:
   - Skip button in top right
   - Illustration area (centered)
   - Title and description text (RTL, right-aligned)
   - Pagination indicators
   - Next button
4. Use Auto Layout with RTL direction
5. Save as a component

### Preference Setup Screen
1. Create a frame with mobile device dimensions
2. Add status bar (Primary Green background)
3. Add header with title and subtitle (RTL, right-aligned)
4. Add content container with:
   - Checkboxes list (RTL)
   - Information card
5. Add bottom navigation with:
   - Progress indicator
   - Back and Next buttons
6. Use Auto Layout with RTL direction
7. Save as a component

### Scanner Screen
1. Create a frame with mobile device dimensions
2. Add status bar and header
3. Add camera viewfinder component
4. Add bottom panel for recent scans
5. Add bottom navigation bar
6. Save as a component

## 11. Implementing Prototype Interactions

1. Select the element that triggers the interaction
2. In the Prototype tab, click "+"
3. Set the interaction:
   - For buttons: On Click → Navigate to / Open overlay
   - For transitions: Choose appropriate animation type and direction
   - For hover states: On Hover → Change to Variant
4. Set duration and easing according to the interactions specifications
5. For complex animations, use Smart Animate with matching layer names across frames

## 12. Documentation Setup

1. Create a new page in your Figma file named "Documentation"
2. Document all color styles, text styles, and components
3. Include usage guidelines and examples
4. Add RTL-specific documentation and tips