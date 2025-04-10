<!DOCTYPE html>

<html lang="en">

<head>

  <meta charset="UTF-8" />

  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <title>HRC Intake Questionnaire</title>

  <style>

    body {

      font-family: sans-serif;

      padding: 1rem;

      max-width: 800px;

      margin: auto;

    }

    h2 {

      border-bottom: 1px solid #ccc;

      padding-bottom: 0.25rem;

    }

    label {

      display: block;

      margin-top: 1rem;

    }

    input, textarea, select {

      width: 100%;

      padding: 0.5rem;

      margin-top: 0.25rem;

      box-sizing: border-box;

    }

    button {

      margin-top: 2rem;

      padding: 0.75rem 1.5rem;

      font-size: 1rem;

    }

    .status {

      margin-top: 1rem;

      color: green;

    }

  </style>

</head>

<body>

  <h1>HRC Intake Questionnaire</h1>

  <form action="https://formsubmit.co/HCPHRC@bccancer.bc.ca" method="POST">

    <input type="hidden" name="_captcha" value="false">

 

    <h2>Patient Information</h2>

    <label>Name: <input type="text" name="name" required></label>

    <label>PHN: <input type="text" name="phn"></label>

    <label>Email address: <input type="email" name="email" required></label>

 

    <label>Can we contact you by email?

      <select name="contact_email" required>

        <option value="">-- Select --</option>

        <option>Yes</option>

        <option>No</option>

      </select>

    </label>

 

    <label>Can we leave you voicemail messages?

      <select name="leave_voicemail" required>

        <option value="">-- Select --</option>

        <option>Yes</option>

        <option>No</option>

      </select>

    </label>

 

    <label>Primary Care Provider: <input type="text" name="provider"></label>

    <label>Home address: <input type="text" name="address"></label>

    <label>Gender/pronouns: <input type="text" name="gender"></label>

 

    <h2>Cancer History</h2>

    <label>Have you had any kind of cancer in the past?

      <select name="cancer_history">

        <option value="">-- Select --</option>

        <option>Yes</option>

        <option>No</option>

      </select>

    </label>

    <label>If yes, type(s) and year(s) of diagnosis: <textarea name="cancer_details"></textarea></label>

 

    <label>Received Chemotherapy/Targeted/Immunotherapy?

      <select name="chemo" required>

        <option value="">-- Select --</option>

        <option>Yes</option>

        <option>No</option>

      </select>

    </label>

 

    <label>Received Radiation?

      <select name="radiation" required>

        <option value="">-- Select --</option>

        <option>Yes</option>

        <option>No</option>

      </select>

    </label>

 

    <label>Received Surgery?

      <select name="surgery" required>

        <option value="">-- Select --</option>

        <option>Yes</option>

        <option>No</option>

      </select>

    </label>

 

    <h2>Breast Imaging (if applicable)</h2>

    <label>Mammogram details: <textarea name="mammogram"></textarea></label>

    <label>Breast MRI details: <textarea name="mri"></textarea></label>

 

    <label>Other imaging completed (e.g., whole-body MRI, PET scan, CT scan):

      <textarea name="other_imaging" placeholder="e.g., Whole-body MRI completed in 2022, no abnormalities found"></textarea>

    </label>

 

    <label>Breast ultrasound details: <textarea name="ultrasound"></textarea></label>

 

    <h2>Gastrointestinal Imaging</h2>

    <label>Colonoscopy details: <textarea name="colonoscopy"></textarea></label>

    <label>Endoscopy details: <textarea name="endoscopy"></textarea></label>

 

    <h2>Gynecological History (if applicable)</h2>

    <label>Age at first period: <input type="number" name="first_period"></label>

    <label>Birth control use (years): <input type="number" name="birth_control_years"></label>

    <label>Number of pregnancies: <input type="number" name="pregnancies"></label>

    <label>Number of children: <input type="number" name="children"></label>

    <label>Age at first childbirth: <input type="number" name="first_child_age"></label>

    <label>Breastfeeding duration: <input type="text" name="breastfeeding"></label>

    <label>Last menstrual period (if menstruating): <input type="date" name="last_period"></label>

    <label>Age at menopause (if post-menopausal): <input type="number" name="menopause_age"></label>

    <label>HRT duration: <input type="text" name="hrt"></label>

    <label>Breast biopsy/surgery details: <textarea name="breast_surgery"></textarea></label>

    <label>Gynecologic surgery details: <textarea name="gyn_surgery"></textarea></label>

 

    <h2>Past Health</h2>

    <label>Health problems: <textarea name="health_problems"></textarea></label>

    <label>Surgeries: <textarea name="surgeries"></textarea></label>

    <label>Medications/Supplements: <textarea name="medications"></textarea></label>

    <label>Allergies and reactions: <textarea name="allergies"></textarea></label>

 

    <h2>Lifestyle</h2>

    <label>Tobacco use details: <textarea name="tobacco"></textarea></label>

    <label>Alcohol (drinks per week): <input type="number" name="alcohol"></label>

    <label>Cannabis/recreational drug use: <textarea name="recreational"></textarea></label>

    <label>Occupation/status: <input type="text" name="occupation"></label>

    <label>Relationship status: <input type="text" name="relationship"></label>

    <label>Exercise habits: <textarea name="exercise"></textarea></label>

 

    <h2>Physical</h2>

    <label>Height: <input type="text" name="height"></label>

    <label>Weight: <input type="text" name="weight"></label>

    <label>Claustrophobia?

      <select name="claustrophobia">

        <option>Yes</option>

        <option>No</option>

      </select>

    </label>

 

    <label>Metal in eye (accident)?

      <select name="metal_eye">

        <option>Yes</option>

        <option>No</option>

      </select>

    </label>

 

    <label>Any metal in your body (e.g., implants, pacemakers, pins)?

      <select name="metal_body">

        <option value="">-- Select --</option>

        <option>Yes</option>

        <option>No</option>

      </select>

    </label>

 

    <label>If yes, please specify type and location:

      <textarea name="metal_body_details" placeholder="e.g., hip implant placed in 2019, dental hardware, pacemaker, etc."></textarea>

    </label>

 

    <h2>Support Needs</h2>

    <label>Interested in research studies?

      <select name="research_interest" required>

        <option value="">-- Select --</option>

        <option>Yes</option>

        <option>No</option>

      </select>

    </label>

 

    <label>Feeling overwhelmed?

      <select name="overwhelmed" required>

        <option value="">-- Select --</option>

        <option>Yes</option>

        <option>No</option>

      </select>

    </label>

 

    <label>Would benefit from care support?

      <select name="need_support" required>

        <option value="">-- Select --</option>

        <option>Yes</option>

        <option>No</option>

      </select>

    </label>

 

    <label>Concerns about mental health impact?

      <select name="mental_health_impact" required>

        <option value="">-- Select --</option>

        <option>Yes</option>

        <option>No</option>

      </select>

    </label>

 

    <label>Have a strong support system?

      <select name="support_system" required>

        <option value="">-- Select --</option>

        <option>Yes</option>

        <option>No</option>

      </select>

    </label>

 

    <label>Interested in emotional support?

      <select name="emotional_support" required>

        <option value="">-- Select --</option>

        <option>Yes</option>

        <option>No</option>

      </select>

    </label>

 

    <label>Experience barriers to access?

      <select name="access_barriers" required>

        <option value="">-- Select --</option>

        <option>Yes</option>

        <option>No</option>

      </select>

    </label>

 

    <button type="submit">Submit</button>

  </form>

  <div class="status">You’ll receive a confirmation email after the first submission is verified.</div>

</body>

</html>
