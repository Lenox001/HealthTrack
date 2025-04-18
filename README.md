# HealthTrack
 </div>
              <span class="badge bg-success rounded-pill">Improving</span>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="col-lg-6">
      <div class="card h-100">
        <div class="card-header bg-success text-white">
          <i class="fas fa-pills icon"></i>Medication Reminders
        </div>
        <div class="card-body p-0">
          <div class="list-group list-group-flush">
            <div class="list-group-item d-flex justify-content-between align-items-center">
              <div>
                <i class="fas fa-capsules me-2" style="color: #6bce70;"></i>
                <strong>Metformin 500mg</strong>
                <div class="text-white small">For Diabetes - Take with breakfast</div>
              </div>
              <div class="d-flex align-items-center">
                <span class="reminder-time me-2">8:00 AM</span>
                <i class="fas fa-bell text-success"></i>
              </div>
            </div>
            <div class="list-group-item d-flex justify-content-between align-items-center">
              <div>
                <i class="fas fa-tablets me-2" style="color: #6bce70;"></i>
                <strong>Lisinopril 10mg</strong>
                <div class="text-white small">For Hypertension - Once daily</div>
              </div>
              <div class="d-flex align-items-center">
                <span class="reminder-time me-2">2:00 PM</span>
                <i class="fas fa-bell text-success"></i>
              </div>
            </div>
            <div class="list-group-item d-flex justify-content-between align-items-center">
              <div>
                <i class="fas fa-inhaler me-2" style="color: #6bce70;"></i>
                <strong>Ventolin Inhaler</strong>
                <div class="text-white small">For Asthma - As needed</div>
              </div>
              <div class="d-flex align-items-center">
                <span class="reminder-time me-2">Before Bed</span>
                <i class="fas fa-bell-slash text-white"></i>
              </div>
            </div>
            <div class="list-group-item d-flex justify-content-between align-items-center">
              <div>
                <i class="fas fa-capsules me-2" style="color: #6bce70;"></i>
                <strong>Atorvastatin 20mg</strong>
                <div class="text-white small">For Cholesterol - At bedtime</div>
              </div>
              <div class="d-flex align-items-center">
                <span class="reminder-time me-2">10:00 PM</span>
                <i class="fas fa-bell text-success"></i>
              </div>
            </div>
          </div>
        </div>
        <div class="card-footer bg-transparent border-top-0 text-end">
          <button class="btn btn-sm btn-outline-success">
            <i class="fas fa-plus me-1"></i>Add Medication
          </button>
        </div>
      </div>
    </div>
  </div>

  <!-- Vitals & Appointments -->
  <div class="row mt-4">
    <div class="col-lg-6">
      <div class="card h-100">
        <div class="card-header bg-info text-white">
          <i class="fas fa-heartbeat icon"></i>Vitals Overview
        </div>
        <div class="card-body">
          <div class="vital-stat">
            <div>
              <span class="text-white">Blood Pressure</span>
              <div class="small text-white">Last reading: Today 8:15 AM</div>
            </div>
            <span class="vital-value">120/80 mmHg</span>
          </div>
          <div class="vital-stat">
            <div>
              <span class="text-white">Blood Sugar</span>
              <div class="small text-white">Fasting - Last reading: Today 8:00 AM</div>
            </div>
            <span class="vital-value">95 mg/dL</span>
          </div>
          <div class="vital-stat">
            <div>
              <span class="text-white">Heart Rate</span>
              <div class="small text-white">Resting - Last reading: Today 8:15 AM</div>
            </div>
            <span class="vital-value">72 bpm</span>
          </div>
          <div class="vital-stat">
            <div>
              <span class="text-white">Weight</span>
              <div class="small text-white">Last reading: Today 8:10 AM</div>
            </div>
            <span class="vital-value">68 kg</span>
          </div>
          <div class="vital-stat">
            <div>
              <span class="text-white">SpO2</span>
              <div class="small text-white">Oxygen Saturation - Last reading: Yesterday</div>
            </div>
            <span class="vital-value">98%</span>
          </div>
        </div>
        <div class="card-footer bg-transparent border-top-0 text-end">
          <button class="btn btn-sm btn-outline-info">
            <i class="fas fa-plus me-1"></i>Record New Vitals
          </button>
        </div>
      </div>
    </div>
    <div class="col-lg-6">
      <div class="card h-100">
        <div class="card-header bg-warning text-dark">
          <i class="fas fa-calendar-check icon"></i>Upcoming Appointments
        </div>
        <div class="card-body p-0">
          <div class="list-group list-group-flush">
            <div class="list-group-item">
              <div class="d-flex justify-content-between align-items-start">
                <div>
                  <i class="fas fa-user-md me-2" style="color: var(--warning);"></i>
                  <strong>Endocrinologist</strong>
                  <div class="text-white small">Dr. Sarah Johnson - Diabetes Management</div>
                </div>
                <span class="badge bg-warning text-dark appointment-badge">Upcoming</span>
              </div>
              <div class="mt-2">
                <i class="far fa-clock me-1"></i>
                <strong>April 22 @ 9:30 AM</strong>
                <span class="text-white ms-2">(3 days from now)</span>
              </div>
              <div class="mt-2">
                <i class="fas fa-map-marker-alt me-1"></i>
                <span>City Medical Center, Suite 405</span>
              </div>
              <div class="mt-3">
                <button class="btn btn-sm btn-outline-warning me-2">
                  <i class="fas fa-directions me-1"></i>Get Directions
                </button>
                <button class="btn btn-sm btn-outline-secondary">
                  <i class="fas fa-calendar-plus me-1"></i>Add to Calendar
                </button>
              </div>
            </div>
            <div class="list-group-item">
              <div class="d-flex justify-content-between align-items-start">
                <div>
                  <i class="fas fa-heartbeat me-2" style="color: var(--warning);"></i>
                  <strong>Cardiologist</strong>
                  <div class="text-white small">Dr. Michael Chen - Hypertension Follow-up</div>
                </div>
                <span class="badge bg-warning text-dark appointment-badge">Upcoming</span>
              </div>
              <div class="mt-2">
                <i class="far fa-clock me-1"></i>
                <strong>May 5 @ 2:00 PM</strong>
                <span class="text-white ms-2">(16 days from now)</span>
              </div>
              <div class="mt-2">
                <i class="fas fa-map-marker-alt me-1"></i>
                <span>Heart & Vascular Institute, Floor 2</span>
              </div>
              <div class="mt-3">
                <button class="btn btn-sm btn-outline-warning me-2">
                  <i class="fas fa-directions me-1"></i>Get Directions
                </button>
                <button class="btn btn-sm btn-outline-secondary">
                  <i class="fas fa-calendar-plus me-1"></i>Add to Calendar
                </button>
              </div>
            </div>
          </div>
        </div>
        <div class="card-footer bg-transparent border-top-0 text-end">
          <button class="btn btn-sm btn-outline-warning me-2">
            <i class="fas fa-plus me-1"></i>Schedule Appointment
          </button>
          <button class="btn btn-sm btn-outline-secondary">
            <i class="fas fa-history me-1"></i>View History
          </button>
        </div>
      </div>
    </div>
  </div>

  <!-- Emergency & Quick Actions -->
  <div class="row mt-4">
    <div class="col-md-12">
      <div class="card">
        <div class="card-header bg-danger text-white">
          <i class="fas fa-exclamation-triangle icon"></i>Emergency & Quick Actions
        </div>
        <div class="card-body">
          <div class="row text-center">
            <div class="col-md-3 col-6 mb-3">
              <button class="btn btn-outline-danger btn-lg rounded-circle p-4" data-bs-toggle="tooltip" data-bs-placement="top" title="Call emergency services">
                <i class="fas fa-ambulance fa-2x"></i>
              </button>
              <div class="mt-2">Emergency</div>
            </div>
            <div class="col-md-3 col-6 mb-3">
              <button class="btn btn-outline-warning btn-lg rounded-circle p-4" data-bs-toggle="tooltip" data-bs-placement="top" title="Contact your primary doctor">
                <i class="fas fa-user-md fa-2x"></i>
              </button>
              <div class="mt-2">Contact Doctor</div>
            </div>
            <div class="col-md-3 col-6 mb-3">
              <button class="btn btn-outline-info btn-lg rounded-circle p-4" data-bs-toggle="tooltip" data-bs-placement="top" title="Find nearby pharmacies">
                <i class="fas fa-prescription-bottle-alt fa-2x"></i>
              </button>
              <div class="mt-2">Find Pharmacy</div>
            </div>
            <div class="col-md-3 col-6 mb-3">
              <button class="btn btn-outline-success btn-lg rounded-circle p-4" data-bs-toggle="tooltip" data-bs-placement="top" title="Log a new symptom">
                <i class="fas fa-notes-medical fa-2x"></i>
              </button>
              <div class="mt-2">Log Symptom</div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- Floating Action Button -->
<div class="fab" data-bs-toggle="tooltip" data-bs-placement="left" title="Quick Help">
  <i class="fas fa-question"></i>
</div>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<script>
  // Initialize tooltips
  document.addEventListener('DOMContentLoaded', function() {
    var tooltipTriggerList = [].slice.call(document.querySelectorAll('[data-bs-toggle="tooltip"]'));
    var tooltipList = tooltipTriggerList.map(function (tooltipTriggerEl) {
      return new bootstrap.Tooltip(tooltipTriggerEl);
    });
    
    // Animate cards on scroll
    const cards = document.querySelectorAll('.card');
    const observer = new IntersectionObserver((entries) => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          entry.target.style.opacity = 1;
          entry.target.style.transform = 'translateY(0)';
        }
      });
    }, { threshold: 0.1 });
    
    cards.forEach(card => {
      card.style.opacity = 0;
      card.style.transform = 'translateY(20px)';
      card.style.transition = 'opacity 0.6s ease, transform 0.6s ease';
      observer.observe(card);
    });
    
    // Form submission
    document.getElementById('checkinForm').addEventListener('submit', function(e) {
      e.preventDefault();
      // Show success animation
      const submitBtn = this.querySelector('button[type="submit"]');
      submitBtn.innerHTML = '<i class="fas fa-check me-2"></i>Submitted!';
      submitBtn.classList.add('btn-success');
      submitBtn.classList.remove('btn-custom');
      
      // Reset after 2 seconds
      setTimeout(() => {
        submitBtn.innerHTML = '<i class="fas fa-paper-plane me-2"></i>Submit Check-In';
        submitBtn.classList.remove('btn-success');
        submitBtn.classList.add('btn-custom');
      }, 2000);
    });
  });
  
  function updateEnergyValue(value) {
    document.getElementById('energyValue').textContent = value;
    
    // Change color based on value
    const energyValue = document.getElementById('energyValue');
    if (value < 4) {
      energyValue.style.color = 'var(--danger)';
    } else if (value < 7) {
      energyValue.style.color = 'var(--warning)';
    } else {
      energyValue.style.color = 'var(--success)';
    }
  }
  
  // Initialize with default energy value
  updateEnergyValue(5);
</script>
</body>
</html>