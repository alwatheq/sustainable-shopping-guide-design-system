# Interactions and Animations

## 1. Onboarding Transitions
- **Slide Transitions:** Horizontal sliding animation between onboarding screens
- **Direction:** RTL (right enters, left exits)
- **Duration:** 300ms
- **Easing:** Ease-in-out
- **Indicators:** Pagination dots animate with fade and size change

## 2. Scanner Interactions
### Camera Activation
- Fade in camera view (duration: 400ms)
- Permission request dialog slides up from bottom
- Viewfinder appears with scale animation (from 80% to 100%, duration: 300ms)

### Scanning Animation
- Horizontal green line moves vertically through viewfinder
- Pulse effect when line passes over barcode
- Duration: Continuous until detection

### Successful Scan
- Viewfinder briefly flashes green
- Haptic feedback (light vibration)
- Circle completion animation (0% to match percentage)
- Results screen slides up (duration: 400ms)

### Failed Scan
- Viewfinder briefly flashes orange
- Error message appears above viewfinder with fade in
- Subtle shake animation
- Automatic retry after 1 second

## 3. Results Screen Interactions
### Tab Switching
- Horizontal slide between tab contents
- Tab indicator animates with smooth transition
- Duration: 250ms
- Content crossfades between tabs

### Match Percentage Animation
- Circle fills clockwise from 0% to final percentage
- Number counts up from 0 to final value
- Duration: 1 second
- Color transitions based on percentage value

### Product Details Expansion
- Cards expand with accordion animation when tapped
- Arrow icon rotates 180°
- Duration: 200ms

### Alternative Products
- Horizontal scroll with momentum
- Snap to product cards
- Shadow effect intensifies on active card

## 4. Preference Selection
### Checkbox Interactions
- Scale animation when tapped (110% briefly, then 100%)
- Color fill animation for checkmark
- Subtle ripple effect
- Duration: 150ms

### Screen Transitions
- Forward: Slide left enter, right exit
- Back: Slide right enter, left exit
- Duration: 300ms

### Progress Indication
- Step indicator smoothly fills
- Step numbers fade and change
- Duration: 250ms

## 5. Error States and Notifications
### Error Messages
- Slide up from bottom with bounce effect
- Red background for critical errors
- Yellow background for warnings
- Auto-dismiss after 3 seconds
- Swipe to dismiss interaction

### Success Messages
- Slide down from top with slight bounce
- Green background
- Check icon pulses once
- Auto-dismiss after 2 seconds

### Loading States
- Circular spinner with Primary Green color
- Pulsing opacity (100% to 60% and back)
- Centered on affected area with slight background dim

## 6. Product Match Animation
- **Initial Load:**
  - Product image scales from 80% to 100%
  - Match circle draws progressively
  - Percentage counters increment from 0 to final value
  - Duration: 1.2 seconds

- **Match Indicators:**
  - Green elements appear with slight bounce
  - Warning elements slide in from right
  - Duration: 200ms staggered timing

## 7. Button States
### Primary Button
- Pressed: Darken color by 15%
- Scale down to 98%
- Release: Return to original color with spring animation
- Disabled: 50% opacity

### Secondary Button
- Pressed: Background fills briefly to 10% green
- Scale down to 98%
- Release: Return to original state with spring animation

### Icon Button
- Pressed: Circle ripple effect from center
- Duration: 300ms

## 8. List Interactions
### Item Selection
- Background color briefly highlights
- Scale up slightly (102%)
- Duration: 150ms

### Swipe to Delete
- Reveal red background with delete icon
- Haptic feedback
- Item width reduces before removal
- Other items slide up to fill space

### Pull to Refresh
- Custom spinner with leaf/moon/shield icons rotating
- Progress circle fills as pull extends
- Release triggers refresh animation
- Content fades in when updated

## 9. Navigation Transitions
### Tab Bar Selection
- Icons scale up briefly (120%) then normalize (100%)
- Color transition from grey to Primary Green
- Subtle bounce effect
- Duration: 200ms

### Screen Transitions
- Main navigation: Crossfade between screens
- Detail screens: Slide up from bottom
- Modal screens: Fade in with scale (95% to 100%)
- Duration: 300ms

## 10. Special Effects
### Product Match Celebration
- For high matches (>90%):
  - Brief confetti effect with eco-friendly icons
  - Green pulse radiating from match percentage
  - Subtle haptic feedback

### Halal Verification Animation
- When halal status is confirmed:
  - Checkmark draws with animated stroke
  - Circular pulse effect
  - Duration: 600ms

### Allergen Warning Animation
- When allergens are detected:
  - Warning icon pulses
  - Yellow highlight animation
  - Duration: 500ms

## 11. Gesture Interactions
### Pinch to Zoom
- On product images
- Smooth zoom with bounce at limits
- Double tap to reset zoom

### Swipe Between Results
- Horizontal swipe between similar products
- Card slides with physics-based momentum
- Indicator dots update

### Long Press
- On product cards in history
- Shows quick actions menu
- Scale up animation (105%)
- Background dim effect

## 12. Microinteractions
### Form Field Focus
- Input field border color animates from grey to Primary Green
- Label moves up and shrinks
- Duration: 200ms

### Toggle Switches
- Thumb slides smoothly
- Track color transitions
- Duration: 150ms

### Rating Selection
- Items scale slightly when selected
- Color fills from left to right
- Subtle bounce on selection