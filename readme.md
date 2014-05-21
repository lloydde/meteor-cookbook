##Meteor Cookbook  

Hi.  Welcome to the Meteor Cookbook; a FAQ and tutorial culled and currated from over 12 months of emails and discussions from the [meteor] google group and my experiences rolling out packages and apps.  These documents are intended for the intermediate user learning Meteor, who is accustomed to a) object-oriented frameworks and languages, such as Java and C#, and b) relational databases and data structures derived from SQL table schemas.  The focus is on helping the user grow accustomed to functional programming using document oriented databases.


##Index  

- [Cookbook Conventions](cookbook-conventions.md)  
- [General Advice](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/general-advice.md)  
- Meteor Style Guide
  - [Terminology](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/terminology.md)  
  - [Syntax](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/syntax.md)  
  - [Punctuation](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/punctuation.md)  
  - [Reserved Keywords](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/reserved.keywords.md)  
- [Installation](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/installation.md)  
  - [Quickstart](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/quickstart.md)  
  - [Development Tools](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/development-tools.md)    
  - [Webstorm IDE](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/webstorm.md)
  - [Test Driven Development](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/test-driven-development.md)  
- Site Mechanics
    - [File Structure](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/filestructure.md)
    - [Dependencies](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/dependencies.md)  
    - [App Structure](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/appstructure.md) 
    - [Event Cycle](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/event-cycle.md) 
    - [Namespacing](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/namespacing.md) 
    - [Packages](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/packages.md)  
    - [Site Configuration](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/configuration.md)  
- Open Systems Interconnection Model
  - Physical Layer
  - Data-Link Layer
    - [Console Logging](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/logging.md)  
    - WebKit Browsers
      - [File IO](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/fileio.md)  
      - [Video IO](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/video.md)  
      - Disk IO  
    - Haptics 
      - [Keybindings](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/keybinding.md)  
      - [Mutlitouch](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/multitouch.md)  
    - Cordova PhoneGap Pipeline
  - Network Layer
    - [Environments](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/environments.md)  
      - [Hosting Providers](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/hosting-providers.md) 
      - [Production](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/environments-production.md)  
      - [Environment Detection](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/environment-detection.md)  
    - [Peer to Peer](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/peer-to-peer.md)  
  - Transport Layer
    - [Scaling](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/scaling.md)  
    - [Data Distribution Protocol](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/ddp.md)  
    - Clustering
    - Websockets
  - [Data Layer](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/datalayer.md)
    - [Schema Design](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/schema-design.md)  
    - Integrating 3rd Party Databases
    - [Collections](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/collections.md)
      - [User Accounts](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/accounts.md)  
      - [Aggregation](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/aggregation.md)  
    - [Schema Migrations](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/schema.changes.md)     
    - [Data Validation](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/validation.md)  
    - [Database Management](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/database-management.md)
    - [Alternative Templating Engines](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/templates.md)  
  - Presentation Layer
    - [Image Assets](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/image-assets.md)  
    - [Animations](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/animations.md)  
  - Application Layer
    - [Routing](https://github.com/EventedMind/iron-router)  
      - [Single Page Design](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/pages.single.md)
      - [Multi-Page Design](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/pages.multi.md)  
      - Multi-Page with Routing
      - [Page Not Found](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/routing.page-not-found.md)  
    - Meteor UI Components
      - [Alerts & Errors](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/pages.alerts.md)  
      - [Accordion](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/accordion.md)    
      - [Modal Dialogs](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/pages.dialogs.md)  
      - [Tabbed Workflow](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/workflow.md)  
      - [Tagging](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/tagging.md)    
      - [Window Resize](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/window.resize.md)  
      - Drop Down Menu
      - Drag and Drop
      - Date Picker
      - Progress Bar
      - Page Transitions
    - Application Programming Interfaces
      - [Integration of 3rd party APIs](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/api-wrappers.md)  
      - [Exposing a REST API](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/rest.md)  
    - Data Driven Documents (D3)  
- [Error Referece](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/errors.md)  
- [Recipes](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/recipes.md)  
  - Blog
  - Cron Workers
  - Collection CRUD
  - [Two-Way Data Binding](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/data-binding.md)  
  - Parsing File Types
    - [XML](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/files.xml.md)   
    - [CSV](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/files.csv.md)  
- [Breaking Changes](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/breaking-news.md)  
- [Recommended Packages](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/packages-we-love.md)  

**In Progress**  
- [Async & Futures](https://gist.github.com/possibilities/3443021)  
- [Database Migrations](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/database-migrations.md)  
- [Data Shaping](https://github.com/awatson1978/meteor-cookbook/blob/master/cookbook/data-shaping.md)




##Applet Demos
Links to live versions of the examples in this cookbook.  

[REST API](http://rest-api.meteor.com/)  
[REST API Testrunner](http://rest-api-testrunner.meteor.com/)    
[GroupThink](http://groupthink.meteor.com/)  
[Fonts & Calligraph](http://fonts.meteor.com/)    
[Dictionary](http://dictionary.meteor.com/)  
[Collabtionary](http://collabtionary.meteor.com/)  
[Hubble - CRUD & Datasets](http://hubble.meteor.com/)  
[Acceptance Testing](http://safety-harness.meteor.com/)  
[Creating Forms](http://forms-kitchen-sink.meteor.com/)  
[Understanding The Rendering Event Loop](http://reactive-rendering-tests.meteor.com/)  
[Mobile Devices - iOS in Particular](https://github.com/awatson1978/cordova-phonegap)  


## Support
Found this package to be useful?  Consider tipping the package maintainer for their time!  

[![Support via Gittip](https://raw.github.com/gittip/www.gittip.com/master/www/assets/gittip.png)](https://www.gittip.com/awatson1978/)  

