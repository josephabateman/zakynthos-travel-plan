# Claude Development Notes

## Project: Zakynthos Travel Plan

### Git Workflow Requirement
**IMPORTANT:** Each time changes are made to any file, always create a git commit first before proceeding.

**Process:**
1. Make changes to files
2. `git add .`
3. `git commit -m "descriptive message"`
4. `git push` (to sync with GitHub/Vercel)
5. Continue with next task

### Project Details
- **GitHub:** https://github.com/josephabateman/zakynthos-travel-plan
- **Live Site:** https://zakynthos-travel.vercel.app
- **User Email:** josephabateman@yahoo.co.uk

### Key Files
- `index.html` - Landing page
- `zakynthos_travel_plan.html` - Interactive map and tabbed itinerary
- `zakynthos_itinerary_overview.html` - Simple location list
- `vercel.json` - Deployment configuration

### Features Completed
- ✅ Corrected all location coordinates
- ✅ Mobile-optimized responsive design
- ✅ Tabbed navigation for days
- ✅ Budget and premium restaurant options
- ✅ Boat rental adventures
- ✅ Focus on secluded beaches
- ✅ GitHub integration with auto-deploy to Vercel

### Important Rules
1. **Always commit changes before moving to next task** - this is a strict requirement!
2. **Location Consistency:** Any updates to locations must be applied to BOTH pages:
   - `zakynthos_travel_plan.html` (interactive map and detailed itinerary)
   - `zakynthos_itinerary_overview.html` (simple location list)
   - All changes must be reflected and consistent across both files