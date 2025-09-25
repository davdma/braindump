# Testing Notes

## Test Cases for Voice Agent

### Authentication Flow
- [ ] Test login with valid credentials
- [ ] Test login with invalid credentials
- [ ] Test password reset functionality
- [ ] Test session timeout handling
- [ ] Test logout functionality

### Voice Recognition
- [ ] Test with clear speech
- [ ] Test with background noise
- [ ] Test with different accents
- [ ] Test with low volume
- [ ] Test with fast/slow speech

### Note Operations
- [ ] Test creating new notes
- [ ] Test reading existing notes
- [ ] Test updating notes
- [ ] Test deleting notes
- [ ] Test searching notes

### Edge Cases
- [ ] Test with no internet connection
- [ ] Test with very long notes
- [ ] Test with special characters
- [ ] Test with empty commands
- [ ] Test with malformed requests

## Bug Reports

### Issue #1: Voice recognition fails in noisy environment
**Priority**: Medium
**Status**: Open
**Description**: Agent struggles to understand commands when background noise is present
**Steps to reproduce**: 
1. Start voice agent
2. Play background music
3. Try to give a command
**Expected**: Agent should understand command
**Actual**: Agent asks for repetition

### Issue #2: Notes not saving properly
**Priority**: High
**Status**: In Progress
**Description**: Sometimes notes are not saved to database
**Steps to reproduce**:
1. Create a new note via voice
2. Check if note appears in list
**Expected**: Note should be saved and visible
**Actual**: Note sometimes missing from list

## Test Data
- Sample notes for testing
- Test user accounts
- Mock voice commands
- Test database entries
