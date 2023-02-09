# BenefitDependency
A simple tool for creating, improving, and publishing a benefit dependency network for business architecture

This is a simple web application.  The front end will be in React.js while the middle tier is likely to be in node.js.  The back end will be a NoSQL database (not determined at this time).  All three tiers are included in this repository.  The details of the stack will emerge in the coming weeks and details will be updated here.

A benefit dependency network (or BDN) is an architectural diagram that illustrates a small handful of relationships in a flattened model.  It exists for three purposes: 
1. To provide a thought model for the architect to flesh out rational business programs
2. To provide a mechanism to illustrate, to a single business stakeholer, the various business and technology programs needed for their business objectives.
3. To act as input to a prioritization exercise by illustrating the overlaps between various stakeholder strategies and the information systems needed to support them.

One benefit to using this type of model is that systems are not developed in a silo, using only the requirements of one area of the business.  Instead, systems are built, improved, consolodated, decommissioned, and managed with respect to all of the stakeholders who need the system to perform well.  By recognizing multiple stakeholders, we reduce the internal pressure, within an organization, to create multiple systems to perform the same (siloed) function.

Another benefit is during the prioritiztion activity that takes place (usually annually) within an organization, that all of the stakeholders can track their particular needs and place them in context of the needs of the company.  This reduces arguments and increases the likelihood that funding to a major program can occur even if it "breaks" the siloed funding mechanisms favored by most enterprises.  In other words, the highest paid person in the room doesn't always get his or her way. 

The primary action of this application is to accept information about goals, strategies, objectives, business programs, and technology changes and to allow them to be mapped to one another is a clear and focused way.  That mapping activity is critical and must be carefully considered.  Using a diagramming tool, like draw.io or visio, the mapping activity is reduced to "drawing a line", making the analysis activity error prone and reducing the value of the resulting model. 

However, just as important to "creating" the diagram, there is a need for presenting the resulting model in two ways: focused on one or more goals / strategies (but keeping the context of the rest of the model in a faded view), and focused on one or more stakeholders where all of the non-relevant detail is simply not shown.  

Creating a diagram for web view is fun, but it is critical that the diagram(s) must be exportable as a PNG for embedding into documents and presentations.  The diagram needs to be versioned, labeled, and easy to export.

At this time, there is no enterprise tool but in the future, there may be.  At MVP, a user can create a BDN and simply dump out the JSON file to save it locally.  Starting up the tool allows the user to import a JSON file to continue analysis and document generation.  In the free version, the user can create an account and can store the BDN in a simple database structure.  In later enterprise versions, the user can identify that the BDN was created for a specific enterprise and can invite other BDN users to collaborate on it with them.  Features that support an enterprise version are post-MVP.

As this project proceeds, we will develop the requirements and demo code and link them to this readme file.  That will allow all participants to see and contribute to the development of the application.  In other words, watch this space.  That said, the entirety of the documentation is not going to be placed into this single readme file.  We will put together a project tracker and provide a link.

This has been a long-standing dream of Nick Malik to produce this project.  I've "spec'ed" it at least four times over the years, always intending to write it myself.  But now that I find myself in the position where I cannot dedicate the time to build this, I am opening up the doors for collaboration. If you wish to ask Nick for direct interaction, please send email to nick@vanguardea.com 
