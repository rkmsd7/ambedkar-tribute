# Data schema
- timeline.json: { eras:[{id,title,years,summary}], events:[{id,date(YYYY-MM-DD),era,title,place,text,tags[],media?(image id)}] }
- images.json: [{id,src(1200px url),full(original url),w,h,caption,alt,date,author,license,source(Commons page),era,event?(timeline event id),hero?:true}]
- videos.json: [{id,youtube(11-char id),title,channel,note?,era}]
- writings.json: { intro, sections:[{title,items:[{year,title,kind,summary,baws?,link?}]}], resources:[{title,url}] }
- speeches.json: { intro, items:[{date,title,venue,quote,context,source,link?}] }
- appearances.json: { intro, items:[{date,title,place,role}] }
- quotes.json: [{text,source}]   vows.json: { intro, vows:[string×22] }
- site.json: { name,title,tagline,occasion,dates,nav:[{href,label}],stats:[{value,label}] }
