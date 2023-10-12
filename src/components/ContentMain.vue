<template>
    <div class="content-main" style="background-color: #f5f9fd;">
        <div class="alert alert-light alert-dismissible fade show pt-0 px-4 pb-0 mb-0" role="alert">
            <div class="d-flex me-4 mb-0 pb-0 justify-content-end">
                <div class="form-group form-check mt-2">
                    <input type="checkbox" class="form-check-input" id="exampleCheck1">
                    <label class="form-check-label" for="exampleCheck1">Don't remind me again</label>
                </div>
            </div>
            <strong style="font-size: 18px; color: black;">Welcome, Mark Anthony!</strong>
            <p><span style="color:rgb(50, 212, 69)">You are almost done!</span> To further strengthen your profile, it is highly recommended for you to complete the 4 sections of your application.</p>
            <button type="button" class="btn-close" data-bs-dismiss="alert" aria-label="Close" style="margin-top: -0.5em; font-size: 10px; color: red"></button>
        </div>
        <div class="alert alert-light show" role="alert">
            <div class="container">
            <div class="row">
                <div class="col">
                    <div class="d-flex gap-2 w-100">
                    <button type="button" class="btn btn-secondary rounded-circle btn-sm" disabled>
                        <svg xmlns="http://www.w3.org/2000/svg" width="21" height="21" fill="currentColor" class="bi bi-person" viewBox="0 0 16 16">
                            <path d="M8 8a3 3 0 1 0 0-6 3 3 0 0 0 0 6Zm2-3a2 2 0 1 1-4 0 2 2 0 0 1 4 0Zm4 8c0 1-1 1-1 1H3s-1 0-1-1 1-4 6-4 6 3 6 4Zm-1-.004c-.001-.246-.154-.986-.832-1.664C11.516 10.68 10.289 10 8 10c-2.29 0-3.516.68-4.168 1.332-.678.678-.83 1.418-.832 1.664h10Z"/>
                        </svg>
                    </button>
                    <div class="text-start mt-1">
                        <p class="mb-0">Application Profile</p>
                        <div class="progress mt-1" style="height: 5px; width: 130px;">
                            <div class="progress-bar bg-warning" role="progressbar" style="width: 75%;" aria-valuemin="0" aria-valuemax="100"></div>
                        </div>
                    </div>   
                    <div class="text-start">
                        <p class="mb-0 mt-3" style="color:coral;">75%</p>
                    </div>            
                    </div>
                </div>
                <div class="col">
                    <div class="d-flex gap-2 w-100">
                    <button type="button" class="btn btn-secondary rounded-circle btn-sm" disabled>
                        <svg xmlns="http://www.w3.org/2000/svg" width="21" height="21" fill="currentColor" class="bi bi-file-earmark-text" viewBox="0 0 16 16">
                            <path d="M5.5 7a.5.5 0 0 0 0 1h5a.5.5 0 0 0 0-1h-5zM5 9.5a.5.5 0 0 1 .5-.5h5a.5.5 0 0 1 0 1h-5a.5.5 0 0 1-.5-.5zm0 2a.5.5 0 0 1 .5-.5h2a.5.5 0 0 1 0 1h-2a.5.5 0 0 1-.5-.5z"/>
                            <path d="M9.5 0H4a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2V4.5L9.5 0zm0 1v2A1.5 1.5 0 0 0 11 4.5h2V14a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V2a1 1 0 0 1 1-1h5.5z"/>
                        </svg>
                    </button>
                    <div class="text-start mt-1">
                        <p class="mb-0">Resume / CV</p>
                        <div class="progress mt-1" style="height: 5px; width: 130px;">
                            <div class="progress-bar bg-danger" role="progressbar" style="width: 50%;" aria-valuemin="0" aria-valuemax="100"></div>
                        </div>
                    </div>   
                    <div class="text-start">
                        <p class="mb-0 mt-3" style="color:rgb(190, 0, 0);">50%</p>
                    </div>            
                    </div>
                </div>
                <div class="col">
                    <div class="d-flex gap-2 w-100">
                    <button type="button" class="btn btn-secondary rounded-circle btn-sm" disabled>
                        <svg xmlns="http://www.w3.org/2000/svg" width="21" height="21" fill="currentColor" class="bi bi-bar-chart-line" viewBox="0 0 16 16">
                            <path d="M11 2a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v12h.5a.5.5 0 0 1 0 1H.5a.5.5 0 0 1 0-1H1v-3a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v3h1V7a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v7h1V2zm1 12h2V2h-2v12zm-3 0V7H7v7h2zm-5 0v-3H2v3h2z"/>
                        </svg>
                    </button>
                    <div class="text-start mt-1">
                        <p class="mb-0">Assessment Score</p>
                        <div class="progress mt-1" style="height: 5px; width: 130px;">
                            <div class="progress-bar bg-danger" role="progressbar" style="width: 20%;" aria-valuemin="0" aria-valuemax="100"></div>
                        </div>
                    </div>   
                    <div class="text-start">
                        <p class="mb-0 mt-3" style="color:rgb(190, 0, 0);">20%</p>
                    </div>            
                    </div>
                </div>
                <div class="col">
                    <div class="d-flex gap-2 w-100">
                    <button type="button" class="btn btn-secondary rounded-circle btn-sm" disabled>
                        <svg xmlns="http://www.w3.org/2000/svg" width="21" height="21" fill="currentColor" class="bi bi-play-btn" viewBox="0 0 16 16">
                            <path d="M6.79 5.093A.5.5 0 0 0 6 5.5v5a.5.5 0 0 0 .79.407l3.5-2.5a.5.5 0 0 0 0-.814l-3.5-2.5z"/>
                            <path d="M0 4a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2V4zm15 0a1 1 0 0 0-1-1H2a1 1 0 0 0-1 1v8a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1V4z"/>
                        </svg>
                    </button>
                    <div class="text-start mt-1">
                        <p class="mb-0">Video Introduction</p>
                        <div class="progress mt-1" style="height: 5px; width: 130px;">
                            <div class="progress-bar bg-danger" role="progressbar" style="width: 30%;" aria-valuemin="0" aria-valuemax="100"></div>
                        </div>
                    </div>   
                    <div class="text-start">
                        <p class="mb-0 mt-3" style="color:rgb(190, 0, 0);">30%</p>
                    </div>            
                    </div>
                </div>
            </div>
            </div>
        </div>
        <div class="row g-5">
            <div class="col-md-8 pe-1">
                <div class="card border border-white">
                <ul class="list-group list-group-flush">
                    <li class="list-group-item p-0">
                        <div class="container">
                            <div class="d-flex row g-6">
                                <div class="mycontent-left col-md-3">
                                    <img src="../assets/profile.jpg" alt="mdo" width="120" height="120" class="rounded-circle border m-3">
                                </div>
                                <div class="col-md-9 p-3 ps-4">
                                    <span style="font-size:23px; font-weight: 500;">Mark Anthony E. Olivares</span>
                                    <br>
                                    <span style="font-size:medium; font-weight: 400"> Front-End Developer</span>
                                    <br>
                                    <div class="mt-3 mb-0">
                                    <span>
                                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-mortarboard-fill me-1" viewBox="0 0 16 16">
                                            <path d="M8.211 2.047a.5.5 0 0 0-.422 0l-7.5 3.5a.5.5 0 0 0 .025.917l7.5 3a.5.5 0 0 0 .372 0L14 7.14V13a1 1 0 0 0-1 1v2h3v-2a1 1 0 0 0-1-1V6.739l.686-.275a.5.5 0 0 0 .025-.917l-7.5-3.5Z"/>
                                            <path d="M4.176 9.032a.5.5 0 0 0-.656.327l-.5 1.7a.5.5 0 0 0 .294.605l4.5 1.8a.5.5 0 0 0 .372 0l4.5-1.8a.5.5 0 0 0 .294-.605l-.5-1.7a.5.5 0 0 0-.656-.327L8 10.466 4.176 9.032Z"/>
                                        </svg>
                                        Bachelor of Science in Information Technology
                                    </span>
                                        <div class="mt-2 mb-0">
                                            <div class="row">
                                                <div class="col-md-4">
                                                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-briefcase-fill me-1" viewBox="0 0 16 16">
                                                        <path d="M6.5 1A1.5 1.5 0 0 0 5 2.5V3H1.5A1.5 1.5 0 0 0 0 4.5v1.384l7.614 2.03a1.5 1.5 0 0 0 .772 0L16 5.884V4.5A1.5 1.5 0 0 0 14.5 3H11v-.5A1.5 1.5 0 0 0 9.5 1h-3zm0 1h3a.5.5 0 0 1 .5.5V3H6v-.5a.5.5 0 0 1 .5-.5z"/>
                                                        <path d="M0 12.5A1.5 1.5 0 0 0 1.5 14h13a1.5 1.5 0 0 0 1.5-1.5V6.85L8.129 8.947a.5.5 0 0 1-.258 0L0 6.85v5.65z"/>
                                                    </svg>
                                                    1 Year
                                                </div>
                                                <div class="col-md-4">
                                                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-calendar-check me-1" viewBox="0 0 16 16">
                                                        <path d="M10.854 7.146a.5.5 0 0 1 0 .708l-3 3a.5.5 0 0 1-.708 0l-1.5-1.5a.5.5 0 1 1 .708-.708L7.5 9.793l2.646-2.647a.5.5 0 0 1 .708 0z"/>
                                                        <path d="M3.5 0a.5.5 0 0 1 .5.5V1h8V.5a.5.5 0 0 1 1 0V1h1a2 2 0 0 1 2 2v11a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2V3a2 2 0 0 1 2-2h1V.5a.5.5 0 0 1 .5-.5zM1 4v10a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1V4H1z"/>
                                                    </svg>
                                                    Immediately
                                                </div>
                                                <div class="col-md-4">
                                                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-coin me-1" viewBox="0 0 16 16">
                                                        <path d="M5.5 9.511c.076.954.83 1.697 2.182 1.785V12h.6v-.709c1.4-.098 2.218-.846 2.218-1.932 0-.987-.626-1.496-1.745-1.76l-.473-.112V5.57c.6.068.982.396 1.074.85h1.052c-.076-.919-.864-1.638-2.126-1.716V4h-.6v.719c-1.195.117-2.01.836-2.01 1.853 0 .9.606 1.472 1.613 1.707l.397.098v2.034c-.615-.093-1.022-.43-1.114-.9H5.5zm2.177-2.166c-.59-.137-.91-.416-.91-.836 0-.47.345-.822.915-.925v1.76h-.005zm.692 1.193c.717.166 1.048.435 1.048.91 0 .542-.412.914-1.135.982V8.518l.087.02z"/>
                                                        <path d="M8 15A7 7 0 1 1 8 1a7 7 0 0 1 0 14zm0 1A8 8 0 1 0 8 0a8 8 0 0 0 0 16z"/>
                                                        <path d="M8 13.5a5.5 5.5 0 1 1 0-11 5.5 5.5 0 0 1 0 11zm0 .5A6 6 0 1 0 8 2a6 6 0 0 0 0 12z"/>
                                                    </svg>
                                                    <span  style="color: rgb(31, 187, 13);">Php 45,000</span>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="position-absolute mt-4 me-4 top-0 end-0">
                                        <div class="form-group form-check">
                                            <svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" fill="currentColor" class="bi bi-pencil" viewBox="0 0 16 16">
                                                <path d="M12.146.146a.5.5 0 0 1 .708 0l3 3a.5.5 0 0 1 0 .708l-10 10a.5.5 0 0 1-.168.11l-5 2a.5.5 0 0 1-.65-.65l2-5a.5.5 0 0 1 .11-.168l10-10zM11.207 2.5 13.5 4.793 14.793 3.5 12.5 1.207 11.207 2.5zm1.586 3L10.5 3.207 4 9.707V10h.5a.5.5 0 0 1 .5.5v.5h.5a.5.5 0 0 1 .5.5v.5h.293l6.5-6.5zm-9.761 5.175-.106.106-1.528 3.821 3.821-1.528.106-.106A.5.5 0 0 1 5 12.5V12h-.5a.5.5 0 0 1-.5-.5V11h-.5a.5.5 0 0 1-.468-.325z"/>
                                            </svg>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </li>
                    <li class="list-group-item">
                        <div class="mt-3 me-2 ms-2">
                            <span style="font-size:18px; font-weight: 500;">General Details</span>
                                <div class="row mt-3">
                                    <div class="details-text col-md-4"><span>Date of Birth</span></div>
                                    <div class="col-md-8">11 June 1999</div>
                                </div>
                                <div class="row  mt-3">
                                    <div class="details-text col-md-4"><span>Gender</span></div>
                                    <div class="col-md-8">Male</div>
                                </div>
                                <div class="row  mt-3">
                                    <div class="details-text col-md-4"><span>Civil Status</span></div>
                                    <div class="col-md-8">Single</div>
                                </div>
                                <div class="row  mt-3 mb-3">
                                    <div class="details-text col-md-4"><span>Nationality</span></div>
                                    <div class="col-md-8">Filipino</div>
                                </div>
                                    <div class="position-absolute mt-4 me-4 top-0 end-0">
                                        <div class="form-group form-check">
                                            <svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" fill="currentColor" class="bi bi-pencil" viewBox="0 0 16 16">
                                                <path d="M12.146.146a.5.5 0 0 1 .708 0l3 3a.5.5 0 0 1 0 .708l-10 10a.5.5 0 0 1-.168.11l-5 2a.5.5 0 0 1-.65-.65l2-5a.5.5 0 0 1 .11-.168l10-10zM11.207 2.5 13.5 4.793 14.793 3.5 12.5 1.207 11.207 2.5zm1.586 3L10.5 3.207 4 9.707V10h.5a.5.5 0 0 1 .5.5v.5h.5a.5.5 0 0 1 .5.5v.5h.293l6.5-6.5zm-9.761 5.175-.106.106-1.528 3.821 3.821-1.528.106-.106A.5.5 0 0 1 5 12.5V12h-.5a.5.5 0 0 1-.5-.5V11h-.5a.5.5 0 0 1-.468-.325z"/>
                                            </svg>
                                        </div>
                                    </div>
                        </div>
                    </li>
                    <li class="list-group-item">
                        <div class="mt-3 me-2 ms-2">
                            <span style="font-size:18px; font-weight: 500;">Professional Status</span>
                                <div class="row mt-3">
                                    <div class="details-text col-md-4"><span>Recent Job Title</span></div>
                                    <div class="col-md-8">Junior Front-End Developer </div>
                                </div>
                                <div class="row  mt-3">
                                    <div class="details-text col-md-4"><span>Interview Availability</span></div>
                                    <div class="col-md-8">-</div>
                                </div>
                                <div class="row  mt-3">
                                    <div class="details-text col-md-4"><span>Current Monthly Salary (Gross)</span></div>
                                    <div class="col-md-8" style="color: rgb(31, 187, 13);">Php 45,000</div>
                                </div>
                                <div class="row  mt-3 mb-3">
                                    <div class="details-text col-md-4"><span>Allowance (Non-Taxable)</span></div>
                                    <div class="col-md-8">-</div>
                                </div>
                                <div class="row  mt-3 mb-3">
                                    <div class="details-text col-md-4"><span>Pre-employment Leaves</span></div>
                                    <div class="col-md-8">-</div>
                                </div>
                                <div class="row  mt-3 mb-3">
                                    <div class="details-text col-md-4"><span>Where can you work?</span></div>
                                    <div class="col-md-8">Office and Home</div>
                                </div>
                                <div class="row  mt-3 mb-3">
                                    <div class="details-text col-md-4"><span>Estimate Travel Time to Office</span></div>
                                    <div class="col-md-8">30 - 50 mins</div>
                                </div>
                                <div class="row  mt-3 mb-3">
                                    <div class="details-text col-md-4"><span>Connection Type</span></div>
                                    <div class="col-md-8">PLDT</div>
                                </div>
                                <div class="row  mt-3 mb-3">
                                    <div class="details-text col-md-4"><span>Website / Portfolio</span></div>
                                    <div class="col-md-8">-</div>
                                </div>
                                    <div class="position-absolute mt-4 me-4 top-0 end-0">
                                        <div class="form-group form-check">
                                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-pencil" viewBox="0 0 16 16">
                                                <path d="M12.146.146a.5.5 0 0 1 .708 0l3 3a.5.5 0 0 1 0 .708l-10 10a.5.5 0 0 1-.168.11l-5 2a.5.5 0 0 1-.65-.65l2-5a.5.5 0 0 1 .11-.168l10-10zM11.207 2.5 13.5 4.793 14.793 3.5 12.5 1.207 11.207 2.5zm1.586 3L10.5 3.207 4 9.707V10h.5a.5.5 0 0 1 .5.5v.5h.5a.5.5 0 0 1 .5.5v.5h.293l6.5-6.5zm-9.761 5.175-.106.106-1.528 3.821 3.821-1.528.106-.106A.5.5 0 0 1 5 12.5V12h-.5a.5.5 0 0 1-.5-.5V11h-.5a.5.5 0 0 1-.468-.325z"/>
                                            </svg>
                                        </div>
                                    </div>
                        </div>
                    </li>
                    <li class="list-group-item">
                        <div class="mt-3 me-2 ms-2">
                            <span style="font-size:18px; font-weight: 500;">Preferences</span>
                                <div class="row mt-3">
                                    <div class="details-text col-md-4"><span>Day Shift</span></div>
                                    <div class="col-md-8">-</div>
                                </div>
                                <div class="row  mt-3">
                                    <div class="details-text col-md-4"><span>Mid Shift</span></div>
                                    <div class="col-md-8">-</div>
                                </div>
                                <div class="row  mt-3">
                                    <div class="details-text col-md-4"><span>Night Shift</span></div>
                                    <div class="col-md-8">-</div>
                                </div>
                                <div class="row  mt-3 mb-3">
                                    <div class="details-text col-md-4"><span>English Only Policy (EOP)</span></div>
                                    <div class="col-md-8">-</div>
                                </div>
                                <div class="row  mt-3 mb-3">
                                    <div class="details-text col-md-4"><span>Where did you hear us?</span></div>
                                    <div class="col-md-8">-</div>
                                </div>
                                <div class="row  mt-3 mb-3">
                                    <div class="details-text col-md-4"><span>Marketing Permission</span></div>
                                    <div class="col-md-8">-</div>
                                </div>
                                <div class="row  mt-3 mb-3">
                                    <div class="details-text col-md-4"><span>Referral</span></div>
                                    <div class="col-md-8">-</div>
                                </div>
                                    <div class="position-absolute mt-4 me-4 top-0 end-0">
                                        <div class="form-group form-check">
                                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-pencil" viewBox="0 0 16 16">
                                                <path d="M12.146.146a.5.5 0 0 1 .708 0l3 3a.5.5 0 0 1 0 .708l-10 10a.5.5 0 0 1-.168.11l-5 2a.5.5 0 0 1-.65-.65l2-5a.5.5 0 0 1 .11-.168l10-10zM11.207 2.5 13.5 4.793 14.793 3.5 12.5 1.207 11.207 2.5zm1.586 3L10.5 3.207 4 9.707V10h.5a.5.5 0 0 1 .5.5v.5h.5a.5.5 0 0 1 .5.5v.5h.293l6.5-6.5zm-9.761 5.175-.106.106-1.528 3.821 3.821-1.528.106-.106A.5.5 0 0 1 5 12.5V12h-.5a.5.5 0 0 1-.5-.5V11h-.5a.5.5 0 0 1-.468-.325z"/>
                                            </svg>
                                        </div>
                                    </div>
                        </div>
                    </li>
                </ul>
                </div>
            </div>

            <div class="col-md-4 ps-4">
                <div class="card border border-white shadow-sm p-1 mb-3 bg-body rounded">
                    <div class="card-header">
                        <span style="font-size:15px; font-weight: 600;">Video Introduction</span>
                    </div>
                    <div class="ratio ratio-4x3">
                        <iframe width="560" height="315" src="https://www.youtube.com/embed/c18441Eh_WE?si=uIaH4JG_Vv0QY7Yc" allowfullscreen></iframe>
                    </div>
                </div>

                <div class="card border border-white shadow-sm p-1 mb-3 bg-body rounded">
                    <div class="card-body">
                        <div class="row">
                            <div class="col-md-9"><span style="font-size:15px; font-weight: 500;">Profile Completion</span></div>
                            <div class="col-md-3 text-end"><span style="font-size:15px; font-weight: 500; color:rgb(9, 169, 9);">100%</span></div>
                        </div>
                            <div class="progress mt-1" style="height: 8px; width: 100%;">
                                <div class="progress-bar bg-success" role="progressbar" style="width: 100%;" aria-valuemin="0" aria-valuemax="100"></div>
                            </div>
                            <div class="text-center mt-4">
                                <span style="color: rgb(31, 187, 13); font-size:16px; font-weight: 600; text-align: center;">Well done, Reyven!</span>
                                    <br>
                                <img src="../assets/medalIcon.png" alt="mdo" width="100" height="80">
                            </div>
                        <p>You have one of the strongest professional profile in our talent pool. Expect progress on your application at any time soon.</p>
                    </div>
                </div>
                <div class="card border border-white shadow-sm p-1 mb-3 bg-body rounded">
                    <div class="card-body">
                        <div class="row">
                            <div class="col-md-9"><span style="font-size:15px; font-weight: 500;">Profile Completion</span></div>
                            <div class="col-md-3 text-end"><span style="font-size:15px; font-weight: 500; color:coral;">50%</span></div>
                        </div>
                            <div class="progress mt-1" style="height: 8px; width: 100%;">
                                <div class="progress-bar bg-warning" role="progressbar" style="width: 50%;" aria-valuemin="0" aria-valuemax="100"></div>
                            </div>
                            
                                <p class="mt-3 ms-3" data-bs-toggle="collapse" href="#collapseExample" role="button" aria-expanded="false" aria-controls="collapseExample">
                                        <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12" fill="currentColor" class="bi bi-chevron-up me-1" viewBox="0 0 16 16">
                                            <path fill-rule="evenodd" d="M7.646 4.646a.5.5 0 0 1 .708 0l6 6a.5.5 0 0 1-.708.708L8 5.707l-5.646 5.647a.5.5 0 0 1-.708-.708l6-6z"/>
                                        </svg>
                                    Hide Recommendations
                                </p>
                            
                                <!-- <p  data-bs-toggle="collapse" href="#collapseExample" role="button" aria-expanded="false" aria-controls="collapseExample">
                                    
                                </p> -->
                            <div class="collapse" id="collapseExample">
                            <div class="card card-body border border-white ms-3 p-0">
                                <p>Fill-up the following items to strengthen your profile. This can help us matching your profile and increase your chances of landing into your desired role.</p>
                                <div class="form-check">
                                <input class="form-check-input" type="radio" name="exampleRadios" id="exampleRadios1" value="option1" checked>
                                <label class="form-check-label" for="exampleRadios1">
                                    Share Date of Birth

                                    
                                </label>
                                </div>
                                <div class="form-check">
                                <input class="form-check-input" type="radio" name="exampleRadios" id="exampleRadios2" value="option2">
                                <label class="form-check-label" for="exampleRadios2">
                                    Specify Current Monthly Salary 
                                </label>
                                </div>
                                <div class="form-check">
                                <input class="form-check-input" type="radio" name="exampleRadios" id="exampleRadios3" value="option3">
                                <label class="form-check-label" for="exampleRadios3">
                                    Add one(1) Character Reference
                                </label>
                                </div>
                                <div class="form-check">
                                <input class="form-check-input" type="radio" name="exampleRadios" id="exampleRadios3" value="option3">
                                <label class="form-check-label" for="exampleRadios3">
                                    Add Current Address
                                </label>
                                </div>
                                <div class="form-check">
                                <input class="form-check-input" type="radio" name="exampleRadios" id="exampleRadios3" value="option3">
                                <label class="form-check-label" for="exampleRadios3">
                                    Add atleast five (5) items in Other Skills
                                </label>
                                </div>
                            </div>
                            </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.mycontent-left {
    border-right: 0.5px solid #cdcdcd;
}
.details-text {
    color: rgb(144, 142, 157); 
    font-weight: 400
}
</style>