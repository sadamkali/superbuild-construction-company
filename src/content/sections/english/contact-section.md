---
enable: true
title: "Have a Construction Project in Mind?"
description: "Tell us what you are planning to build, renovate, or improve and our team will get back to you."
officeHours: "Office Hours: Mon - Sat: 8:00 AM - 6:00 PM"

formTitle: "Request a Quote"
formDescription: "Share a few details about your project and we will contact you with the next steps."

form:
  emailSubject: "New construction project enquiry"
  submitButton:
    enable: true
    label: "Send Enquiry"
    class: "w-full justify-center rounded-md"
    hoverEffect: "magnetic-text-flip"

  inputs:
    - label: "Your name"
      name: "Name"
      placeholder: "Your name"
      required: true
      halfWidth: true
    - label: "Phone number"
      name: "Phone"
      placeholder: "Phone number"
      type: "tel"
      required: true
      halfWidth: true
    - label: "Email address"
      name: "Email"
      placeholder: "Email address"
      type: "email"
      halfWidth: true
    - label: "Estimated budget"
      name: "Budget"
      placeholder: "Estimated budget"
      type: "text"
      halfWidth: true
    - label: "Project type"
      name: "Project Type"
      placeholder: "Select a project type"
      required: true
      dropdown:
        type: "search"
        search:
          placeholder: "Search project type"
        items:
          - label: "Residential Construction"
            value: "Residential Construction"
          - label: "Commercial Construction"
            value: "Commercial Construction"
          - label: "Renovation & Remodeling"
            value: "Renovation & Remodeling"
          - label: "Roofing"
            value: "Roofing"
          - label: "Concrete & Structural Works"
            value: "Concrete & Structural Works"
          - label: "Finishing Works"
            value: "Finishing Works"
          - label: "Site Preparation & Excavation"
            value: "Site Preparation & Excavation"
          - label: "Project Management"
            value: "Project Management"
    - label: "Preferred start date"
      name: "Start Date"
      placeholder: "Preferred start date"
      type: "date"
      halfWidth: true
    - label: "Project location"
      name: "Location"
      placeholder: "Where is the project located?"
      halfWidth: true
    - label: "Tell us about your project"
      name: "Message"
      placeholder: "Tell us what you would like us to build or work on"
      tag: "textarea"
      rows: "5"
      required: true
    - label: "I agree to be contacted about this enquiry."
      name: "Consent"
      value: true
      type: "checkbox"
      required: true
    - note: success
      parentClass: "hidden text-sm message success"
      content: "Thank you. We received your enquiry and will contact you soon."
    - note: deprecated
      parentClass: "hidden text-sm message error"
      content: "Something went wrong. Please try again or contact us directly."
---
