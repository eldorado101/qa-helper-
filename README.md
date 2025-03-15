QA Wikipedia Helper
Description
The QA Wikipedia Helper is a WordPress plugin designed to answer user questions by pulling data from multiple sources, including:

Wikipedia
DuckDuckGo Instant Answer API
Google Knowledge Graph API
This plugin is ideal for websites that need a simple Q&A system with dark theme support. It also includes an Analytics Dashboard to track user queries, feedback, and data source usage.

Features
Multi-Source Answers : Fetch answers from Wikipedia, DuckDuckGo, and Google Knowledge Graph.
Feedback System : Allow users to provide feedback (👍/👎) on answers.
Analytics Dashboard :
View total queries, most popular queries, feedback stats, and data source usage.
Integrate with Peepso to display usernames and profile links.
Caching : Improve performance by caching API responses.
Customizable Settings : Configure API keys for Google Knowledge Graph.
Dark Theme Support : Styling optimized for dark-themed websites.
Voice Search : Enable voice-based question submission.
Installation
Step 1: Upload the Plugin
Download the plugin files as a .zip archive.
Go to your WordPress admin dashboard.
Navigate to Plugins > Add New .
Click Upload Plugin , select the .zip file, and click Install Now .
Activate the plugin through the Plugins menu.
Step 2: Manual Installation
Extract the plugin files from the .zip archive.
Upload the qa-wikipedia-helper folder to the /wp-content/plugins/ directory.
Activate the plugin through the Plugins menu in WordPress.
Configuration
Step 1: Set Up API Keys
Go to Settings > QA Wikipedia Helper in your WordPress admin dashboard.
Enter your Google Knowledge Graph API Key .
Save the settings.
Step 2: Use the Shortcode
Add the following shortcode to any page or post where you want the Q&A form to appear:

php
Copy
1
[qa_wikipedia_helper]
Step 3: Access the Analytics Dashboard
Navigate to the QA Analytics menu in the WordPress admin sidebar.
View analytics data, including:
Total queries
Most popular queries
Feedback stats
Data source usage
Usage
Asking Questions
Users can type their questions into the input field.
Select a data source (DuckDuckGo, Wikipedia, or Google Knowledge Graph).
Submit the form to view the answer.
Providing Feedback
After receiving an answer, users can click the 👍 (positive) or 👎 (negative) buttons to provide feedback.
Feedback is logged in the database and displayed in the Analytics Dashboard.
Voice Search
Click the 🎤 button to enable voice search (requires browser microphone access).
Requirements
PHP 7.0+
WordPress 5.0+
API Keys (optional for Google Knowledge Graph)
Frequently Asked Questions (FAQ)
Q1: Why do I need an API key for Google Knowledge Graph?
A: The Google Knowledge Graph API requires an API key to fetch structured data about entities. Without it, the plugin will skip this data source.

Q2: Can I use this plugin without Peepso?
A: Yes! The plugin works independently of Peepso. If Peepso is not installed, it will display WordPress usernames instead.

Q3: How does caching work?
A: The plugin caches API responses for 24 hours using WordPress transients. This reduces the number of API calls and improves performance.

Q4: What happens if an API fails?
A: If an API fails to return results, the plugin will fall back to other data sources or display a "No results found" message.


Q&A Form : A clean, dark-themed form for submitting questions.
Analytics Dashboard : Displays query statistics, feedback, and data source usage.
Settings Page : Configure API keys and other plugin settings.
Changelog
Version 1.5
Added user_id column to the qa_analytics table for better user tracking.
Integrated Peepso usernames/profile links into the Analytics Dashboard.
Improved error handling and logging.
Version 1.0
Initial release with basic functionality.
Support
If you encounter any issues or have feature requests, please contact us at:

Email : dakota@contentsocial.net
Website : https://www.contentsocial.net/


Credits
DuckDuckGo API : https://duckduckgo.com/api
Google Knowledge Graph API : https://developers.google.com/knowledge-graph
WordPress Codex : https://developer.wordpress.org
License
This plugin is released under the GNU General Public License v2 or later (GPL-2.0-or-later) . You are free to use, modify, and distribute this plugin as long as you comply with the license terms.

