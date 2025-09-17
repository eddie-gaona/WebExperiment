# Amplitude Analytics & Web Experiments Demo

This website demonstrates the integration of Amplitude Browser SDK and Web Experiment script using the provided API key.

## 🚀 Features

- **Amplitude Browser SDK Integration**: Complete analytics tracking setup
- **Web Experiment Script**: A/B testing and experimentation capabilities  
- **Anti-Flicker Implementation**: Smooth loading without content flashing
- **Interactive Demo**: Live event tracking demonstrations
- **Real-time Event Logging**: See events as they're sent to Amplitude
- **Responsive Design**: Works on desktop and mobile devices

## 🔧 Integration Details

### API Key
- **Amplitude API Key**: `21a79579d9e9996ce5cc452d8e2f043c`

### Components Included

1. **Amplitude Browser SDK**
   - Latest version with async loading
   - Proper initialization with your API key
   - Event tracking capabilities
   - User identification features

2. **Web Experiment Script**
   - Anti-flicker snippet for smooth user experience
   - Asynchronous loading for better performance
   - Ready for A/B testing and experiments

3. **Demo Features**
   - Page view tracking
   - Button click events
   - Custom event examples
   - User identification
   - Experiment interaction tracking

## 🎯 How to Use

1. **Open the Website**: Simply open `index.html` in your web browser
2. **Test Event Tracking**: Click the demo buttons to send events to Amplitude
3. **Monitor Events**: Watch the real-time event log to see what's being tracked
4. **Check Integration Status**: The status section shows if both SDKs loaded correctly

## 📊 Event Tracking Examples

The demo includes several types of events:

- **Page View**: Tracks when the page loads
- **Button Click**: Tracks user interactions with buttons
- **Custom Events**: Demonstrates custom event properties
- **User Identification**: Shows how to identify users
- **Experiment Interactions**: Tracks A/B test variant interactions

## 🧪 Web Experiments

The website includes a demo section for testing different experiment variants:

- **Variant A**: Control version
- **Variant B**: Test version

Click on the variant cards to trigger experiment interaction events.

## 🔍 Monitoring & Debugging

- **Event Log**: Real-time display of all events being sent
- **Integration Status**: Visual indicators showing SDK loading status
- **Event Counter**: Tracks total number of events sent
- **Console Logging**: Check browser console for additional debugging info

## 📱 Browser Compatibility

This integration works with all modern browsers that support:
- ES6 JavaScript features
- CSS Grid and Flexbox
- Modern DOM APIs

## 🚀 Going Live

To use this in production:

1. Replace the demo content with your actual website content
2. Customize the event tracking for your specific use cases
3. Set up experiments in the Amplitude dashboard
4. Configure proper CSP headers if needed:
   ```
   Content-Security-Policy: script-src *.amplitude.com unsafe-inline;
   Cross-Origin-Opener-Policy: unsafe-none
   ```

## 📈 Next Steps

1. **Create Experiments**: Use the Amplitude dashboard to create web experiments
2. **Set Up Funnels**: Track user journeys through your site
3. **Configure Cohorts**: Segment users based on behavior
4. **Set Up Alerts**: Get notified about important metrics changes

---

Built with ❤️ using Amplitude Analytics and Web Experimentation
