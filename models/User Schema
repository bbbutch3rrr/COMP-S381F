const mongoose = require('mongoose');

// Simple User Schema for Authentication
const userSchema = new mongoose.Schema({
    username: { type: String, required: true, unique: true },
    password: { type: String, required: true } // In a real app, hash this!
});

module.exports = mongoose.model('User', userSchema);
