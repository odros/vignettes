## Mongo
- How to query Mongo for non-empty fields: db.videos.findOne({ comments: { $exists: true, $ne: [] } })
