db.todo.insertOne({'Task': 'Meeting', 'Status': 'False'});
db.todo.find({'Task': 'Meeting'});
db.todo.updateOne({'Task': 'Meeting'}, { $set: { 'Status': 'True' } });
db.todo.deleteOne({'Task': 'Meeting'});
