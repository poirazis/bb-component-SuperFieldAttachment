# Super Field - Attachment

A file upload component for Budibase applications with drag-and-drop support, file validation, and attachment management.

## 🚀 Features

### File Upload

- **Single File Upload**: Dedicated attachment field for one file
- **Drag & Drop**: Intuitive drag-and-drop file selection
- **File Browser**: Traditional file selection dialog
- **Preview Support**: File type icons and information display
- **Default Values**: Pre-selected default files

### File Management

- **File Validation**: Size, type, and format restrictions
- **Template Formatting**: Custom file display formatting
- **Event Handling**: On change events with file context
- **State Management**: Disabled and readonly modes

### User Experience

- **Visual Feedback**: Upload progress and status indicators
- **Error Handling**: Clear error messages for upload failures
- **Auto-focus**: Automatic focus for file selection
- **Help Text**: Guidance for file requirements and formats
- **Accessibility**: Keyboard navigation and screen reader support

### Advanced Features

- **Button Integration**: Custom upload action buttons
- **Conditional Logic**: Dynamic behavior based on file state
- **File Preview**: Thumbnail or icon preview of uploaded files
- **Metadata**: File size, type, and upload date information

### Styling & Layout

- **Flexible Positioning**: Label placement options
- **Field Modes**: Form input or inline editing
- **Size Configuration**: Adjustable component width
- **Theme Integration**: Consistent with Budibase design

## 📝 Usage Instructions

### Basic Setup

1. Add the Super Field - Attachment component to your form
2. Bind to an attachment field in your data source
3. Configure file validation rules (size, type)
4. Set help text for file requirements

### Advanced Configuration

- **File Types**: Specify allowed file extensions
- **Size Limits**: Set maximum file size restrictions
- **Validation**: Configure upload requirements
- **Events**: Attach actions to file upload completion

### Common Use Cases

- **Document Upload**: PDF, Word, and text documents
- **Image Upload**: Profile pictures and media files
- **Certificate Storage**: License and certification files
- **Resume Submission**: Job application attachments
- **Evidence Files**: Supporting documentation

## 🔧 Configuration Options

| Setting         | Type       | Description                  |
| --------------- | ---------- | ---------------------------- |
| Field           | Attachment | Single file attachment field |
| Label           | String     | Display label text           |
| Placeholder     | String     | Upload guidance text         |
| Default Value   | File       | Pre-selected default file    |
| Formatted Value | Template   | File display formatting      |
| Help Text       | String     | Help/instruction text        |
| Validation      | Rules      | File validation (size/type)  |
| Autofocus       | Boolean    | Auto-focus on load           |
| Disabled        | Boolean    | Disable file upload          |
| Read Only       | Boolean    | Read-only mode               |
| Field Mode      | Select     | Form or inline input style   |
| Label Position  | Select     | Label placement              |
| Size            | Number     | Component width span         |

## 📋 Events

### On Change

Triggered when a file is uploaded or changed.

**Context:**

- `value`: The uploaded file information
- `field`: The bound field information

## 🎨 Styling

The component integrates with Budibase's styling system:

- **Upload Zone**: Visual drag-and-drop area
- **File Icons**: Type-specific file representations
- **Progress Indicators**: Upload progress visualization
- **Error States**: Clear error message styling

## 🔍 Best Practices

- Specify clear file type and size requirements
- Provide help text for accepted file formats
- Consider mobile users for file upload UX
- Implement proper error handling for upload failures
- Use appropriate file size limits for performance
- Test file upload on various devices and browsers
