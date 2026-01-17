- Plan
  collapsed:: true
	- Prerequisites
	  collapsed:: true
		- preprocessing
			- DONE [[butterworth bandpass filter]]
			- DONE [[Temporal Derivative Distribution Repair]]
			- LATER [[baseline correction]]
		- analysis
			- DOING [[General Linear Model]]
			  :LOGBOOK:
			  CLOCK: [2024-06-12 Wed 00:22:46]
			  CLOCK: [2024-06-12 Wed 00:22:54]
			  :END:
			- DOING [[t-test]]
			  :LOGBOOK:
			  CLOCK: [2024-06-12 Wed 00:23:00]
			  CLOCK: [2024-06-12 Wed 00:23:05]
			  :END:
			- DOING [[ANOVA]]
			  :LOGBOOK:
			  CLOCK: [2024-06-12 Wed 02:00:15]
			  CLOCK: [2024-06-12 Wed 02:00:18]
			  :END:
			- TODO [[bonferroni post hoc]]
			- TODO [[Geisser-Greenhouse correction]]
			- TODO [[Pearson correlation coefficient]]
	- activities
		- DOING [[Meeting with Dr Lim Lam Ghai]]
		  :LOGBOOK:
		  CLOCK: [2024-06-12 Wed 00:28:00]
		  CLOCK: [2024-06-12 Wed 00:28:05]
		  :END:
	- dataset
		- DOING [[dataset detail]]
		  :LOGBOOK:
		  CLOCK: [2024-06-12 Wed 01:07:39]
		  :END:
		- LATER manual labelling
		  :LOGBOOK:
		  CLOCK: [2024-06-12 Wed 00:24:15]--[2024-06-12 Wed 00:24:15] =>  00:00:00
		  CLOCK: [2024-06-12 Wed 00:24:16]--[2024-06-12 Wed 00:24:16] =>  00:00:00
		  CLOCK: [2024-06-12 Wed 00:24:25]--[2024-06-12 Wed 00:24:26] =>  00:00:01
		  CLOCK: [2024-06-12 Wed 00:24:26]--[2024-06-12 Wed 00:24:27] =>  00:00:01
		  :END:
	- research
		- LATER perform experiments at [[University Teknologi Petronas]]
	- paper
		- LATER paper 1
		- LATER paper 2
- PhD duration: july 2024 ~ march 2027
- Milestone
  collapsed:: true
	- **Date**: Tuesday, 22 July 2025
	  **Time**: 10:00 AM – 11:00 AM (MYT)
	  **Supervisors**:
	  Main - Dr. Alpha Agape Gopalai
	  Co- Dr. Lim Lam Ghai
	- **Chair of Milestone:**  Assoc. Prof. Joanne Lim
	  **Panelists:** Dr. Maxine Tan, Dr.  Khong Wei Leong
	- **Research Title**: 
	  An adaptive block-design paradigm with a novel deep learning-assisted approach for better cognitive load estimation
	- **Research Summary**:
	- Functional near-infrared spectroscopy (fNIRS) is a neuroimaging technique that indirectly measures neuronal activity via the hemodynamic response (HR). In recent years, fNIRS-based brain-computer interfaces have shown tremendous potential in assessing cognitive state. Adopting the conventional block-design paradigm, a control block is fixed after each task block to allow the evoked HR to return to the baseline. However, several studies have reported that improper baseline recovery may occur, causing large variabilities in the observed brain activations to the extent that affects result interpretations. This implies that the individual’s evoked HR requires different amounts of time to recover to baseline. Hence, we aim to enhance cognitive load estimation by proposing an adaptive block-design paradigm with a novel deep learning-assisted approach. First, a proof of concept will be conducted by identifying and labeling 2000 recorded fNIRS data containing a variety of 15-s hemodynamic responses into four classes; (i) optimal baseline, (ii) suboptimal baseline, (iii) activation, and (iv) oscillation. Several promising deep learning techniques, i.e., convolutional neural network, long short-term memory, and transformer, will be used to train the data. Another fNIRS dataset, recorded from 40 participants performing multiple difficulty levels of mental arithmetic, will be used to assess the effectiveness of the proposed method. Using the most suitable deep learning technique, the proposed method will be applied in a real-time setup to optimize the control duration accordingly. A new task block will begin whenever the proposed method detects a proper neural baseline recovery. We expect to observe a significant improvement in cognitive load estimation as compared to the conventional block-design paradigm. This novel project will be the first study to attempt an adaptive block-design paradigm, offering a practical and promising solution to assess and diagnose cognitive impairments, such as in individuals with Alzheimer’s disease.
- Brief summary
  collapsed:: true
	- {{renderer :wordcount_}}/
		- The study aims to enhance cognitive load estimation using fNIRS by proposing an adaptive block-design paradigm with deep learning. This method optimizes task timing based on neural baseline recovery, improving state assessment and aiding cognitive impairment diagnosis.
	- {{renderer :wordcountchar_}}
		- Functional near-infrared spectroscopy (fNIRS) is a neuroimaging technique that indirectly measures neuronal activity via the hemodynamic response (HR). In recent years, fNIRS-based brain-computer interfaces have shown tremendous potential in assessing cognitive state. Adopting the conventional block-design paradigm, a control block is fixed after each task block to allow the evoked HR to return to the baseline. However, several studies have reported that improper baseline recovery may occur, causing large variabilities in the observed brain activations to the extent that affects result interpretations. This implies that the individual’s evoked HR requires different amounts of time to recover to baseline. Hence, we aim to enhance cognitive load estimation by proposing an adaptive block-design paradigm with a novel deep learning-assisted approach. First, a proof of concept will be conducted by identifying and labeling 2000 recorded fNIRS data containing a variety of 15-s hemodynamic responses into four classes; (i) optimal baseline, (ii) suboptimal baseline, (iii) activation, and (iv) oscillation. Several promising deep learning techniques, i.e., convolutional neural network, long short-term memory, and transformer, will be used to train the data. Another fNIRS dataset, recorded from 40 participants performing multiple difficulty levels of mental arithmetic, will be used to assess the effectiveness of the proposed method. Using the most suitable deep learning technique, the proposed method will be applied in a real-time setup to optimize the control duration accordingly. A new task block will begin whenever the proposed method detects a proper neural baseline recovery. We expect to observe a significant improvement in cognitive load estimation as compared to the conventional block-design paradigm. This novel project will be the first study to attempt an adaptive block-design paradigm, offering a practical and promising solution to assess and diagnose cognitive impairments, such as in individuals with Alzheimer’s disease.
- Abstract
  collapsed:: true
	- {{renderer :wordcount_}}
		- Functional near-infrared spectroscopy (fNIRS) is a neuroimaging technique that indirectly measures neuronal activity via the hemodynamic response (HR). In recent years, fNIRS-based brain-computer interfaces have shown tremendous potential in assessing cognitive state. Adopting the conventional **block-design** paradigm, a control block is fixed after each task block to allow the **evoked HR** to return to the **baseline**. However, several studies have reported that **improper baseline recovery** may occur, causing large variabilities in the observed brain activations to the extent that affects result interpretations. This implies that the individual’s evoked HR requires different amounts of time to recover to baseline. Hence, we aim to enhance cognitive load estimation by proposing an adaptive block-design paradigm with a novel deep learning-assisted approach. First, **a proof of concept will be conducted by identifying and labeling 2000 recorded fNIRS data containing a variety of 15-s hemodynamic responses into four classes; (i) optimal baseline, (ii) suboptimal baseline, (iii) activation, and (iv) oscillation**. Several promising deep learning techniques, i.e., convolutional neural network, long short-term memory, and transformer, will be used to train the data. Another fNIRS dataset, recorded from 40 participants performing multiple difficulty levels of mental arithmetic, will be used to assess the effectiveness of the proposed method. Using the most suitable deep learning technique, the proposed method will be applied in a **real-time** setup to optimize the control duration accordingly. A new task block will **begin whenever the proposed method detects a proper neural baseline recovery**. We expect to observe a significant improvement in cognitive load estimation as compared to the conventional block-design paradigm. This novel project will be the first study to attempt an adaptive block-design paradigm, offering a practical and promising solution to assess and diagnose cognitive impairments, such as in individuals with Alzheimer’s disease.
	- 6-month review
		- {{renderer :wordcount_}}
			- Key Research Topic
			  Functional near-infrared spectroscopy (fNIRS) is a neuroimaging technique that indirectly measures neuronal activity via the hemodynamic response (HR). In recent years, fNIRS-based brain-computer interfaces have shown tremendous potential in assessing cognitive state. The conventional block-design paradigm in fNIRS studies employs a fixed control block after each task block to allow the evoked HR to return to the baseline. However, improper baseline recovery has been reported in several studies, causing large variabilities in observed brain activations and complicating result interpretations. Individual variations in HR recovery time necessitate an adaptive approach. This research aims to enhance cognitive load estimation by proposing an adaptive block-design paradigm with a novel deep learning-assisted approach.
			  
			  Detailed Research Questions
			  How can the variability in hemodynamic responses caused by improper baseline recovery be quantified and addressed in fNIRS-based experiments?
			  What are the critical features in hemodynamic response data that indicate baseline recovery, and how can these be effectively classified using deep learning?
			  Which deep learning architecture (CNN, LSTM, Transformer) performs best in accurately classifying baseline recovery states, and why?
			  How does the proposed adaptive block-design paradigm improve the accuracy and reliability of cognitive load estimation compared to the conventional block-design paradigm?
			  Can real-time detection of baseline recovery enhance the applicability of fNIRS for diagnosing cognitive impairments?
			  
			  Methods
			  A proof of concept will involve identifying and labeling 2000 recorded fNIRS data containing 15-second hemodynamic responses into four categories; (i) optimal baseline, (ii) suboptimal baseline, (iii) activation and (iv) oscillation. Several promising deep learning techniques, i.e., convolutional neural network, long short-term memory, and transformer, will be used to train the data. The proposed adaptive method will then be validated using an fNIRS dataset collected from 40 participants performing mental arithmetic tasks at varying difficulty levels. Next, the method will be implemented in a real-time setup to adjust control block durations dynamically. A new task block will begin only after proper neural baseline recovery is detected by the proposed model. The effectiveness of the adaptive block-design paradigm will be evaluated by comparing its cognitive load estimation accuracy to that of the conventional paradigm.
- Proposal
  collapsed:: true
	- Abstract
	- Introduction
	- {{renderer :wordcount_}}
		- Functional brain imaging techniques are vital tools for delving into the complexities of neural function and cognition. Among these techniques, functional magnetic resonance imaging (fMRI) has long been the go-to, providing unparalleled spatial resolution and coverage of the entire brain. However, in recent years, there has been a notable increase in the use of functional near-infrared spectroscopy (fNIRS) to study neurovascular coupling dynamics. This shift is driven by several factors, including the portability and cost-effectiveness of fNIRS systems, as well as their reduced susceptibility to motion artifacts. Additionally, fNIRS offers a higher temporal resolution compared to fMRI, enabling more precise tracking of rapid changes in hemodynamic responses. Another advantage of fNIRS is its ability to measure concentration changes in both oxygenated and deoxygenated hemoglobin, providing a more comprehensive assessment of cerebral hemodynamics.
		  
		  However, both fMRI and fNIRS face challenges when using conventional block-design paradigms for estimating cognitive load. These paradigms typically involve alternating periods of task stimulation and rest to allow task-evoked hemodynamic responses to return to baseline levels. However, determining the optimal duration of rest periods is a critical issue, especially with longer task durations. Prolonged recovery times require control periods of equal or greater duration to ensure accurate baseline measurements. Additionally, individual differences in hemodynamic response characteristics, influenced by factors such as age and clinical conditions, introduce variability in recovery times across different populations. In essence, the challenge of determining the appropriate duration of rest periods is compounded by the inherent variability in hemodynamic responses among individuals and experimental conditions. This variability presents a significant obstacle to accurately estimating cognitive load using conventional block-design paradigms.
		  
		  Therefore, the rigid structure of conventional block designs limits their adaptability to individual differences and dynamic changes in cognitive demands. As a result, relying on fixed rest periods in block-design experiments may lead to inaccurate assessments of cognitive load, compromising the reliability and validity of study findings. In the most severe instances, improper return of baseline could distort the temporal characteristics of task-induced hemodynamic responses, potentially resulting in misinterpretation of detected activations.
	- **Research questions**
		- is this research gap?
	- Hypothesis
		- We expect to observe a significant improvement in cognitive load estimation as compared to the conventional block-design paradigm.
	- Objectives
	- Literature review
		- [[cHRF]] analysis
			- [[GLM]]
			- assumption:
				- neural activity function is correct
				- HRF is correct
				- [[cHRF]] is [[LTI]] system
		- cognitive load estimation
			- average of activation amplitude
			- [[GLM]]
				- [[t-test]]
				- [[p-value]]
				- activation region
	- Methodology
		- type of cognitive task
			- what is the purpose of baseline return detection
		- labelling (multi-channel)
			- Dataset
				- first-stage (**training** and **testing**)
					- a proof of concept will be conducted by identifying and labeling 2000 recorded fNIRS data containing a variety of 15-s hemodynamic responses into four classes; (i) optimal baseline, (ii) suboptimal baseline, (iii) activation, and (iv) oscillation.
				- second-stage (**validation**)
					- Another fNIRS dataset, recorded from 40 participants performing multiple difficulty levels of mental arithmetic, will be used to assess the effectiveness of the proposed method.
- Overview
  collapsed:: true
	- [[fNIRS]] 
	  ![fNIRS.jpg](../assets/fNIRS_1709720671786_0.jpg)
- Journal
	- Papers
		- First paper: Adaptive HRF
		  collapsed:: true
			- PSO record
			  collapsed:: true
				- dataset: P1_02
				  collapsed:: true
					- hrf_param_20250408.mat
					  collapsed:: true
						- subject: 1 ~ 17
						- P_lb_hbo = [0 4 2 2 0 0];
						  P_ub_hbo = [3 8 10 8 0.1 0.5];
						  P_lb_hbr = [0 4 4 2 0 0];
						  P_ub_hbr = [4.5 14 10 12 0.25 0.25];
						- function t = glm_cos_hrf_t2(parameter, freq, hbo, unit)
						      
						      num_particle = size(parameter,1); % each row represents one particle
						     
						      half_cosine_hrf = parallel_cos_hrf6(parameter,freq);
						  
						      glm_hrf = conv2(unit,half_cosine_hrf');
						      glm_hrf = glm_hrf(1:length(unit),:)';
						      offset = ones(num_particle,length(unit));
						      X = cat(3,glm_hrf,offset);
						  
						      % solve linear equation: y_hbo = glm_hrf * beta
						      % y_hbo [t_len*1*num_particle]
						      % design_matrix [t_len*2*num_particle]
						      % beta [2*num_particle]
						      y_hbo = repmat(hbo',1,1,num_particle);
						      design_matrix = permute(X,[2 3 1]);
						      beta = squeeze(pagelsqminnorm(design_matrix,y_hbo));
						  
						      X_reshaped = permute(X, [3, 2, 1]);
						      beta_reshaped = permute(beta,[1 3 2]);
						      y_pho = sum(X_reshaped .* beta_reshaped,1);
						      est_y = permute(y_pho,[3 2 1]);
						      sse = sum((est_y - hbo).^2, 2);
						  
						      beta_negative = beta(1,:)' < 0;
						      t_peak = sum(parameter(:,1:2),2);
						      t_peak_invalid = t_peak > 7;
						      beta_polarity = sign(beta(1,:)');
						      t = sse + beta_negative .* t_peak_invalid .* exp(-beta_polarity .* t_peak / 7);
						  
						      
						      % t = sse + beta_negative * 1e10;
						  end
					- hrf_param_20250409.mat
					  collapsed:: true
						- P_lb_hbo = [0 4 2 2 0 0];
						  P_ub_hbo = [3 8 10 8 0.1 0.5];
						  P_lb_hbr = [0 4 2 2 0 0];
						  P_ub_hbr = [4.5 14 10 12 0.25 0.5];
						  tolerance = 0.1;
						- function t = glm_cos_hrf_t_error(parameter, freq, hbo, unit, tolerance)
						      
						      num_particle = size(parameter,1); % each row represents one particle
						     
						      half_cosine_hrf = parallel_cos_hrf6(parameter,freq);
						  
						      glm_hrf = conv2(unit,half_cosine_hrf');
						      glm_hrf = glm_hrf(1:length(unit),:)';
						      offset = ones(num_particle,length(unit));
						      X = cat(3,glm_hrf,offset);
						  
						      % solve linear equation: y_hbo = glm_hrf * beta
						      % y_hbo [t_len*1*num_particle]
						      % design_matrix [t_len*2*num_particle]
						      % beta [2*num_particle]
						      y_hbo = repmat(hbo',1,1,num_particle);
						      design_matrix = permute(X,[2 3 1]);
						      beta = squeeze(pagelsqminnorm(design_matrix,y_hbo));
						  
						      X_reshaped = permute(X, [3, 2, 1]);
						      beta_reshaped = permute(beta,[1 3 2]);
						      y_pho = sum(X_reshaped .* beta_reshaped,1);
						      est_y = permute(y_pho,[3 2 1]);
						      sse = sum((est_y - hbo).^2, 2);
						  
						      beta_negative = beta(1,:)' < 0;
						      penalty = tolerance * min(sse);
						      t = sse + beta_negative .* penalty;
						  end
					- hrf_param_20250410.mat
					  collapsed:: true
						- P_lb_hbo = [0 4 2 2 0 0];
						  P_ub_hbo = [3 8 10 8 0.1 0.5];
						  P_lb_hbr = [0 4 2 2 0 0];
						  P_ub_hbr = [4.5 14 10 12 0.25 0.5];
						  tolerance = 0.05;
						- function t = glm_cos_hrf_t_error(parameter, freq, hbo, unit, tolerance)
						      
						      num_particle = size(parameter,1); % each row represents one particle
						     
						      half_cosine_hrf = parallel_cos_hrf6(parameter,freq);
						  
						      glm_hrf = conv2(unit,half_cosine_hrf');
						      glm_hrf = glm_hrf(1:length(unit),:)';
						      offset = ones(num_particle,length(unit));
						      X = cat(3,glm_hrf,offset);
						  
						      % solve linear equation: y_hbo = glm_hrf * beta
						      % y_hbo [t_len*1*num_particle]
						      % design_matrix [t_len*2*num_particle]
						      % beta [2*num_particle]
						      y_hbo = repmat(hbo',1,1,num_particle);
						      design_matrix = permute(X,[2 3 1]);
						      beta = squeeze(pagelsqminnorm(design_matrix,y_hbo));
						  
						      X_reshaped = permute(X, [3, 2, 1]);
						      beta_reshaped = permute(beta,[1 3 2]);
						      y_pho = sum(X_reshaped .* beta_reshaped,1);
						      est_y = permute(y_pho,[3 2 1]);
						      sse = sum((est_y - hbo).^2, 2);
						  
						      beta_negative = beta(1,:)' < 0;
						      penalty = tolerance * min(sse);
						      t = sse + beta_negative .* penalty;
						  end
					- hrf_param_20250411.mat
					  collapsed:: true
						- identical to [[Optimizing the general linear model for fNIRS - an adaptive hemodynamic response function approach]]
						- P_lb_hbo = [0 4 2 2 0 0];
						  P_ub_hbo = [3 8 10 8 0.1 0.5];
						  P_lb_hbr = [0 4 2 2 0 0];
						  P_ub_hbr = [4.5 14 10 12 0.25 0.5];
						- function t = glm_cos_hrf_t(parameter, freq, hbo, unit)
						      
						      num_particle = size(parameter,1); % each row represents one particle
						     
						      half_cosine_hrf = parallel_cos_hrf6(parameter,freq);
						  
						      glm_hrf = conv2(unit,half_cosine_hrf');
						      glm_hrf = glm_hrf(1:length(unit),:)';
						      offset = ones(num_particle,length(unit));
						      X = cat(3,glm_hrf,offset);
						  
						      % solve linear equation: y_hbo = glm_hrf * beta
						      % y_hbo [t_len*1*num_particle]
						      % design_matrix [t_len*2*num_particle]
						      % beta [2*num_particle]
						      y_hbo = repmat(hbo',1,1,num_particle);
						      design_matrix = permute(X,[2 3 1]);
						      beta = squeeze(pagelsqminnorm(design_matrix,y_hbo));
						  
						      n = length(hbo);
						      p = 2;
						      X_reshaped = permute(X, [3, 2, 1]);
						      beta_reshaped = permute(beta,[1 3 2]);
						      y_pho = sum(X_reshaped .* beta_reshaped,1);
						      est_y = permute(y_pho,[3 2 1]);
						      sigma2_hat = sum((est_y - hbo).^2, 2) / (n - p);
						  
						      mean_x1 = mean(glm_hrf,2);
						      var_x1 = sum((glm_hrf - mean_x1).^2, 2);
						      se_b1 = sqrt(sigma2_hat ./ var_x1);
						  
						      t = - beta(1,:)' ./ se_b1;
						      
						  end
					- hrf_param_20250417.mat
					  collapsed:: true
						- P_lb_hbo = [0 4 2 2 0 0];
						  P_ub_hbo = [3 8 10 8 0.1 0.5];
						  P_lb_hbr = [0 4 2 2 0 0];
						  P_ub_hbr = [4.5 14 10 12 0.25 0.5];
						  tolerance = 0.15;
						- function t = glm_cos_hrf_t_error(parameter, freq, hbo, unit, tolerance)
						      
						      num_particle = size(parameter,1); % each row represents one particle
						     
						      half_cosine_hrf = parallel_cos_hrf6(parameter,freq);
						  
						      glm_hrf = conv2(unit,half_cosine_hrf');
						      glm_hrf = glm_hrf(1:length(unit),:)';
						      offset = ones(num_particle,length(unit));
						      X = cat(3,glm_hrf,offset);
						  
						      % solve linear equation: y_hbo = glm_hrf * beta
						      % y_hbo [t_len*1*num_particle]
						      % design_matrix [t_len*2*num_particle]
						      % beta [2*num_particle]
						      y_hbo = repmat(hbo',1,1,num_particle);
						      design_matrix = permute(X,[2 3 1]);
						      beta = squeeze(pagelsqminnorm(design_matrix,y_hbo));
						  
						      X_reshaped = permute(X, [3, 2, 1]);
						      beta_reshaped = permute(beta,[1 3 2]);
						      y_pho = sum(X_reshaped .* beta_reshaped,1);
						      est_y = permute(y_pho,[3 2 1]);
						      sse = sum((est_y - hbo).^2, 2);
						  
						      beta_negative = beta(1,:)' < 0;
						      penalty = tolerance * min(sse);
						      t = sse + beta_negative .* penalty;
						  end
					- hrf_param_20250514mat
					  collapsed:: true
						- P_lb_hbo = [0 4 2 2 0 0];
						  P_ub_hbo = [3 8 10 8 0.1 0.5];
						  P_lb_hbr = [0 4 2 2 0 0];
						  P_ub_hbr = [4.5 14 10 12 0.25 0.5];
						  tolerance = 0.2;
						- function t = glm_cos_hrf_t_error(parameter, freq, hbo, unit, tolerance)
						      
						      num_particle = size(parameter,1); % each row represents one particle
						     
						      half_cosine_hrf = parallel_cos_hrf6(parameter,freq);
						  
						      glm_hrf = conv2(unit,half_cosine_hrf');
						      glm_hrf = glm_hrf(1:length(unit),:)';
						      offset = ones(num_particle,length(unit));
						      X = cat(3,glm_hrf,offset);
						  
						      % solve linear equation: y_hbo = glm_hrf * beta
						      % y_hbo [t_len*1*num_particle]
						      % design_matrix [t_len*2*num_particle]
						      % beta [2*num_particle]
						      y_hbo = repmat(hbo',1,1,num_particle);
						      design_matrix = permute(X,[2 3 1]);
						      beta = squeeze(pagelsqminnorm(design_matrix,y_hbo));
						  
						      X_reshaped = permute(X, [3, 2, 1]);
						      beta_reshaped = permute(beta,[1 3 2]);
						      y_pho = sum(X_reshaped .* beta_reshaped,1);
						      est_y = permute(y_pho,[3 2 1]);
						      sse = sum((est_y - hbo).^2, 2);
						  
						      beta_negative = beta(1,:)' < 0;
						      penalty = tolerance * min(sse);
						      t = sse + beta_negative .* penalty;
						  end
					- hrf_param_20250609.mat
					  collapsed:: true
						- P_lb_hbo = [0 4 2 2 0 0];
						  P_ub_hbo = [3 8 10 8 0.1 0.5];
						  P_lb_hbr = [0 4 2 2 0 0];
						  P_ub_hbr = [4.5 14 10 12 0.25 0.5];
						  tolerance = 0;
						- function t = glm_cos_hrf_t_error(parameter, freq, hbo, unit, tolerance)
						      
						      num_particle = size(parameter,1); % each row represents one particle
						     
						      half_cosine_hrf = parallel_cos_hrf6(parameter,freq);
						  
						      glm_hrf = conv2(unit,half_cosine_hrf');
						      glm_hrf = glm_hrf(1:length(unit),:)';
						      offset = ones(num_particle,length(unit));
						      X = cat(3,glm_hrf,offset);
						  
						      % solve linear equation: y_hbo = glm_hrf * beta
						      % y_hbo [t_len*1*num_particle]
						      % design_matrix [t_len*2*num_particle]
						      % beta [2*num_particle]
						      y_hbo = repmat(hbo',1,1,num_particle);
						      design_matrix = permute(X,[2 3 1]);
						      beta = squeeze(pagelsqminnorm(design_matrix,y_hbo));
						  
						      X_reshaped = permute(X, [3, 2, 1]);
						      beta_reshaped = permute(beta,[1 3 2]);
						      y_pho = sum(X_reshaped .* beta_reshaped,1);
						      est_y = permute(y_pho,[3 2 1]);
						      sse = sum((est_y - hbo).^2, 2);
						  
						      beta_negative = beta(1,:)' < 0;
						      penalty = tolerance * min(sse);
						      t = sse + beta_negative .* penalty;
						  end
				- dataset: P1_01
				  collapsed:: true
					- hrf_param_20250423.mat
					  collapsed:: true
						- P_lb_hbo = [0 4 2 2 0 0];
						  P_ub_hbo = [3 8 10 8 0.1 0.5];  
						  P_lb_hbr = [0 4 2 2 0 0];  
						  P_ub_hbr = [4.5 14 10 12 0.25 0.5];  
						  tolerance = 0.1;
						- function t = glm_cos_hrf_t_error(parameter, freq, hbo, unit, tolerance)
						        
						      num_particle = size(parameter,1); % each row represents one particle  
						       
						      half_cosine_hrf = parallel_cos_hrf6(parameter,freq);  
						    
						      glm_hrf = conv2(unit,half_cosine_hrf');  
						      glm_hrf = glm_hrf(1:length(unit),:)';  
						      offset = ones(num_particle,length(unit));  
						      X = cat(3,glm_hrf,offset);  
						    
						      % solve linear equation: y_hbo = glm_hrf * beta  
						      % y_hbo [t_len*1*num_particle]  
						      % design_matrix [t_len*2*num_particle]  
						      % beta [2*num_particle]
						      y_hbo = repmat(hbo',1,1,num_particle);
						      design_matrix = permute(X,[2 3 1]);
						      beta = squeeze(pagelsqminnorm(design_matrix,y_hbo));
						  
						      X_reshaped = permute(X, [3, 2, 1]);
						      beta_reshaped = permute(beta,[1 3 2]);
						      y_pho = sum(X_reshaped .* beta_reshaped,1);  
						      est_y = permute(y_pho,[3 2 1]);  
						      sse = sum((est_y - hbo).^2, 2);  
						    
						      beta_negative = beta(1,:)' < 0;  
						      penalty = tolerance * min(sse);  
						      t = sse + beta_negative .* penalty;  
						  end
					- hrf_param_20250427.mat
					  collapsed:: true
						- P_lb_hbo = [0 4 2 2 0 0];
						  P_ub_hbo = [3 8 10 8 0.1 0.5];  
						  P_lb_hbr = [0 4 2 2 0 0];  
						  P_ub_hbr = [4.5 14 10 12 0.25 0.5];  
						  tolerance = 0.15;
						- function t = glm_cos_hrf_t_error(parameter, freq, hbo, unit, tolerance)
						        
						      num_particle = size(parameter,1); % each row represents one particle  
						       
						      half_cosine_hrf = parallel_cos_hrf6(parameter,freq);  
						    
						      glm_hrf = conv2(unit,half_cosine_hrf');  
						      glm_hrf = glm_hrf(1:length(unit),:)';  
						      offset = ones(num_particle,length(unit));  
						      X = cat(3,glm_hrf,offset);  
						    
						      % solve linear equation: y_hbo = glm_hrf * beta  
						      % y_hbo [t_len*1*num_particle]  
						      % design_matrix [t_len*2*num_particle]  
						      % beta [2*num_particle]
						      y_hbo = repmat(hbo',1,1,num_particle);
						      design_matrix = permute(X,[2 3 1]);
						      beta = squeeze(pagelsqminnorm(design_matrix,y_hbo));
						  
						      X_reshaped = permute(X, [3, 2, 1]);
						      beta_reshaped = permute(beta,[1 3 2]);
						      y_pho = sum(X_reshaped .* beta_reshaped,1);  
						      est_y = permute(y_pho,[3 2 1]);  
						      sse = sum((est_y - hbo).^2, 2);  
						    
						      beta_negative = beta(1,:)' < 0;  
						      penalty = tolerance * min(sse);  
						      t = sse + beta_negative .* penalty;  
						  end
					- hrf_param_20250428.mat
					  collapsed:: true
						- P_lb_hbo = [0 4 2 2 0 0];
						  P_ub_hbo = [3 8 10 8 0.1 0.5];  
						  P_lb_hbr = [0 4 2 2 0 0];  
						  P_ub_hbr = [4.5 14 10 12 0.25 0.5];  
						  tolerance = 0.05;
						- function t = glm_cos_hrf_t_error(parameter, freq, hbo, unit, tolerance)
						        
						      num_particle = size(parameter,1); % each row represents one particle  
						       
						      half_cosine_hrf = parallel_cos_hrf6(parameter,freq);  
						    
						      glm_hrf = conv2(unit,half_cosine_hrf');  
						      glm_hrf = glm_hrf(1:length(unit),:)';  
						      offset = ones(num_particle,length(unit));  
						      X = cat(3,glm_hrf,offset);  
						    
						      % solve linear equation: y_hbo = glm_hrf * beta  
						      % y_hbo [t_len*1*num_particle]  
						      % design_matrix [t_len*2*num_particle]  
						      % beta [2*num_particle]
						      y_hbo = repmat(hbo',1,1,num_particle);
						      design_matrix = permute(X,[2 3 1]);
						      beta = squeeze(pagelsqminnorm(design_matrix,y_hbo));
						  
						      X_reshaped = permute(X, [3, 2, 1]);
						      beta_reshaped = permute(beta,[1 3 2]);
						      y_pho = sum(X_reshaped .* beta_reshaped,1);  
						      est_y = permute(y_pho,[3 2 1]);  
						      sse = sum((est_y - hbo).^2, 2);  
						    
						      beta_negative = beta(1,:)' < 0;  
						      penalty = tolerance * min(sse);  
						      t = sse + beta_negative .* penalty;  
						  end
					- param_hrf_20250430.mat
					  collapsed:: true
						- tolerance = 0.1;
						  P_lb_hbo = [0 4 2 2 0 0];
						  P_ub_hbo = [3 8 10 8 0.1 0.5];
						  P_lb_hbr = [0 4 2 2 0 0];
						  P_ub_hbr = [4.5 14 10 12 0.25 0.5];
						- param_adaptive_hrf_pso.m
						- function t = glm_cos_hrf_t_error(parameter, freq, hbo, unit, tolerance)
						      
						      num_particle = size(parameter,1); % each row represents one particle
						     
						      half_cosine_hrf = parallel_cos_hrf6(parameter,freq);
						  
						      glm_hrf = conv2(unit,half_cosine_hrf');
						      glm_hrf = glm_hrf(1:length(unit),:)';
						      offset = ones(num_particle,length(unit));
						      X = cat(3,glm_hrf,offset);
						  
						      % solve linear equation: y_hbo = glm_hrf * beta
						      % y_hbo [t_len*1*num_particle]
						      % design_matrix [t_len*2*num_particle]
						      % beta [2*num_particle]
						      y_hbo = repmat(hbo',1,1,num_particle);
						      design_matrix = permute(X,[2 3 1]);
						      beta = squeeze(pagelsqminnorm(design_matrix,y_hbo));
						  
						      X_reshaped = permute(X, [3, 2, 1]);
						      beta_reshaped = permute(beta,[1 3 2]);
						      y_pho = sum(X_reshaped .* beta_reshaped,1);
						      est_y = permute(y_pho,[3 2 1]);
						      sse = sum((est_y - hbo).^2, 2);
						  
						      beta_negative = beta(1,:)' < 0;
						      penalty = tolerance * min(sse);
						      t = sse + beta_negative .* penalty;
						  end
					- param_hrf_20250501.mat
					  collapsed:: true
						- tolerance = 0.05;
						  P_lb_hbo = [0 4 2 2 0 0];
						  P_ub_hbo = [3 8 10 8 0.1 0.5];
						  P_lb_hbr = [0 4 2 2 0 0];
						  P_ub_hbr = [4.5 14 10 12 0.25 0.5];
						- param_adaptive_hrf_pso.m
						- function t = glm_cos_hrf_t_error(parameter, freq, hbo, unit, tolerance)
						      
						      num_particle = size(parameter,1); % each row represents one particle
						     
						      half_cosine_hrf = parallel_cos_hrf6(parameter,freq);
						  
						      glm_hrf = conv2(unit,half_cosine_hrf');
						      glm_hrf = glm_hrf(1:length(unit),:)';
						      offset = ones(num_particle,length(unit));
						      X = cat(3,glm_hrf,offset);
						  
						      % solve linear equation: y_hbo = glm_hrf * beta
						      % y_hbo [t_len*1*num_particle]
						      % design_matrix [t_len*2*num_particle]
						      % beta [2*num_particle]
						      y_hbo = repmat(hbo',1,1,num_particle);
						      design_matrix = permute(X,[2 3 1]);
						      beta = squeeze(pagelsqminnorm(design_matrix,y_hbo));
						  
						      X_reshaped = permute(X, [3, 2, 1]);
						      beta_reshaped = permute(beta,[1 3 2]);
						      y_pho = sum(X_reshaped .* beta_reshaped,1);
						      est_y = permute(y_pho,[3 2 1]);
						      sse = sum((est_y - hbo).^2, 2);
						  
						      beta_negative = beta(1,:)' < 0;
						      penalty = tolerance * min(sse);
						      t = sse + beta_negative .* penalty;
						  end
					- param_hrf_20250502.mat
					  collapsed:: true
						- tolerance = 0.15;
						  P_lb_hbo = [0 4 2 2 0 0];
						  P_ub_hbo = [3 8 10 8 0.1 0.5];
						  P_lb_hbr = [0 4 2 2 0 0];
						  P_ub_hbr = [4.5 14 10 12 0.25 0.5];
						- param_adaptive_hrf_pso.m
						- function t = glm_cos_hrf_t_error(parameter, freq, hbo, unit, tolerance)
						      
						      num_particle = size(parameter,1); % each row represents one particle
						     
						      half_cosine_hrf = parallel_cos_hrf6(parameter,freq);
						  
						      glm_hrf = conv2(unit,half_cosine_hrf');
						      glm_hrf = glm_hrf(1:length(unit),:)';
						      offset = ones(num_particle,length(unit));
						      X = cat(3,glm_hrf,offset);
						  
						      % solve linear equation: y_hbo = glm_hrf * beta
						      % y_hbo [t_len*1*num_particle]
						      % design_matrix [t_len*2*num_particle]
						      % beta [2*num_particle]
						      y_hbo = repmat(hbo',1,1,num_particle);
						      design_matrix = permute(X,[2 3 1]);
						      beta = squeeze(pagelsqminnorm(design_matrix,y_hbo));
						  
						      X_reshaped = permute(X, [3, 2, 1]);
						      beta_reshaped = permute(beta,[1 3 2]);
						      y_pho = sum(X_reshaped .* beta_reshaped,1);
						      est_y = permute(y_pho,[3 2 1]);
						      sse = sum((est_y - hbo).^2, 2);
						  
						      beta_negative = beta(1,:)' < 0;
						      penalty = tolerance * min(sse);
						      t = sse + beta_negative .* penalty;
						  end
			- [[AR-IRLS]] result
				- dataset: P1_02
					- ARIRLS_20250426.mat
					  collapsed:: true
						- [b,a]=butter(3,[0.01/(10/2) 0.2/(10/2)]); %bandpass filter
						- method_names = {'fixed hrf GLM' '3hrf GLM' '3hrf RGLM' 'optimised hrf GLM' 'adaptive hrf GLM T5' 'adaptive hrf GLM T10' 'adaptive hrf GLM T15' 'Gaussian basis FIR' 'Tent basis FIR'};
					- ARIRLS_20250427.mat
					  collapsed:: true
						- [b,a]=butter(3,0.01/(10/2),"high"); %high pass filter
						- method_names = {'fixed hrf GLM' '3hrf GLM' '3hrf RGLM' 'optimised hrf GLM' 'adaptive hrf GLM T5' 'adaptive hrf GLM T10' 'adaptive hrf GLM T15' 'Gaussian basis FIR' 'Tent basis FIR'};
					- ARIRLS_20250516.mat
					  collapsed:: true
						- [b,a]=butter(3,0.01/(10/2),"high"); %high pass filter
						- method_names = {'fixed hrf GLM' '3hrf GLM' '3hrf RGLM' 'optimised hrf GLM' 'BA optimised hrf GLM' 'adaptive hrf GLM T5' 'adaptive hrf GLM T10' 'adaptive hrf GLM T15' 'adaptive hrf GLM T20' 'Gaussian basis FIR' 'Tent basis FIR'};
					- ARIRLS_20250517.mat
					  collapsed:: true
						- [b,a]=butter(3,[0.01/(10/2) 0.2/(10/2)]); %bandpass filter
						- method_names = {'fixed hrf GLM' '3hrf GLM' '3hrf RGLM' 'optimised hrf GLM' 'BA optimised hrf GLM' 'adaptive hrf GLM T5' 'adaptive hrf GLM T10' 'adaptive hrf GLM T15' 'adaptive hrf GLM T20' 'Gaussian basis FIR' 'Tent basis FIR'};
					- ARIRLS_20250520.mat
					  collapsed:: true
						- from scratch
						- baseline with aid of intercept
						- filter_hbo = hbo_hp_mc(channel_num,:);
						              filter_hbr = hbr_hp_mc(channel_num,:);
						  
						              % for visualization
						              hbo_viz = zeros(total_method_num+1,length(stimulus));
						              hbr_viz = zeros(total_method_num+1,length(stimulus));
						              hbo_viz(end,:) = hbo_bp_mc(channel_num,:); % last is HbO reading
						              hbr_viz(end,:) = hbr_bp_mc(channel_num,:); % last is HbR reading
						- method_names = {'fixed hrf GLM' '3hrf GLM' '3hrf RGLM' 'optimised hrf GLM' 'BA optimised hrf GLM' 'adaptive hrf GLM T5' 'adaptive hrf GLM T10' 'adaptive hrf GLM T15' 'adaptive hrf GLM T20' 'Gaussian basis FIR' 'Tent basis FIR'};
					- ARIRLS_20250521.mat
					  collapsed:: true
						- from scratch
						- filter_hbo = hbo_bp_mc(channel_num,:);
						              filter_hbr = hbr_bp_mc(channel_num,:);
						  
						              % for visualization
						              hbo_viz = zeros(total_method_num+1,length(stimulus));
						              hbr_viz = zeros(total_method_num+1,length(stimulus));
						              hbo_viz(end,:) = hbo_bp_mc(channel_num,:); % last is HbO reading
						              hbr_viz(end,:) = hbr_bp_mc(channel_num,:); % last is HbR reading
						- method_names = {'fixed hrf GLM' '3hrf GLM' '3hrf RGLM' 'optimised hrf GLM' 'BA optimised hrf GLM' 'adaptive hrf GLM T5' 'adaptive hrf GLM T10' 'adaptive hrf GLM T15' 'adaptive hrf GLM T20' 'Gaussian basis FIR' 'Tent basis FIR'};
				- dataset: P1_01
					- ARIRLS_20250518.mat
					  collapsed:: true
						- [b,a]=butter(3,0.01/(10/2),"high"); %high pass filter
						- method_names = {'fixed hrf GLM' '3hrf GLM' '3hrf RGLM' 'optimised hrf GLM' 'BA optimised hrf GLM' 'adaptive hrf GLM T5' 'adaptive hrf GLM T10' 'adaptive hrf GLM T15' 'adaptive hrf GLM T20' 'Gaussian basis FIR' 'Tent basis FIR'}
					- ARIRLS_20250519.mat
					  collapsed:: true
						- [b,a]=butter(3,[0.01/(10/2) 0.2/(10/2)]); %bandpass filter
						- method_names = {'fixed hrf GLM' '3hrf GLM' '3hrf RGLM' 'optimised hrf GLM' 'BA optimised hrf GLM' 'adaptive hrf GLM T5' 'adaptive hrf GLM T10' 'adaptive hrf GLM T15' 'adaptive hrf GLM T20' 'Gaussian basis FIR' 'Tent basis FIR'}
			- target
			  collapsed:: true
				- (i) IEEE Transactions on Medical Imaging, impact factor 8.9, Q1
				- (ii) IEEE Journal of Biomedical and Health Informatics, if 6.8, Q1
				- (iii) IEEE Transactions on Neural Systems and Rehabilitation Engineering if 5.2, Q1
			- objective
			  collapsed:: true
				- design GLM design matrix
					- robust to variability in HRF shape
						- [[initial dip]]
						- [[post stimulus undershoot]]
					- robust to noise ([[autoregression]] model)
			- graphical abstract
			  collapsed:: true
				- {{renderer :wordcount_}}
					- Within the General Linear Model (GLM) framework, the proposed method (A) leverages adaptive hemodynamic response function (HRF) to accommodate hemodynamic heterogeneous which reflect true activation amplitude, and (B) introduces physiology-based polarity-constrained regularization to reject implausible HRF shapes that would misinterpret the initial dip or the post-stimulus undershoot as the activation peak.
				- {{renderer :wordcount_}}
					- Within General Linear Model (GLM) framework, the proposed method (A) leverages adaptive hemodynamic response function (HRF) to accommodate hemodynamic heterogeneity and thus accurately reflect true activation amplitude,  and (B) introduces physiology-constrained regularization to reject implausible HRF shapes that would misinterpret the initial dip or post-stimulus undershoot as the activation peak.
			- abstract
			  collapsed:: true
				- {{renderer :wordcount_}}
					- Functional near-infrared spectroscopy (fNIRS) is a noninvasive neuroimaging technique that uses near-infrared light to measure cortical hemodynamic changes by quantifying changes of oxyhemoglobin (HbO) and deoxyhemoglobin (HbR) concentrations. Variations in the hemodynamic response across individuals and brain regions present a persistent challenge for fNIRS activation detection, often leading to reduced sensitivity or false positives when using fixed‑shape hemodynamic response function (HRF) models. To address this, we propose a novel approach that incorporates fully parametric HRF modeling for each individual and measurement channel, employing broad HRF's paramaters bounds to maximize adaptability to subject and brain region specific hemodynamics. Model parameters are estimated via particle swarm optimization (PSO), a population‑based global search algorithm that resists entrapment in local minima even under expansive search domains. To ensure physiological plausibility and mitigate overfitting, we introduce a regularization scheme that enforces positive peaks for HbO and negative peaks for HbR, thereby systematically rejecting insensible HRF shapes. We evaluated our method against seven established baseline approaches using a block‑design dataset collected from the prefrontal cortex (PFC) of 37 participants performing a mental workload task. The proposed approach demonstrates superior sensitivity and specificity, as it reliably detects positive HbO and negative HbR activations in expected task-evoked brain regions while preserving the characteristic inverse relationship between the two signals. Specifically, activations were observed in the dorsolateral prefrontal cortex (DLPFC), intraparietal sulcus (IPS), and supramarginal gyrus, which correspond to Brodmann areas 9, 46, and 40. We provide open-source software implementing our method.
				- {{renderer :wordcount_}}
					- Functional near-infrared spectroscopy is a noninvasive neuroimaging technique that uses near-infrared light to measure cortical hemodynamic changes by quantifying changes in oxyhemoglobin (HbO) and deoxyhemoglobin (HbR) concentrations. Variations in the hemodynamic response across individuals and brain regions present a persistent challenge for fNIRS activation detection, often leading to reduced sensitivity or false positives when using fixed‑shape hemodynamic response function (HRF) models. To address this, we propose a novel approach that incorporates fully parametric HRF modeling for each individual and measurement channel, employing broad HRF parameter bounds to maximize adaptability to subject and brain region-specific hemodynamics. The model parameters were estimated via particle swarm optimization, a population-based global search algorithm that resists entrapment in local minima, even under expansive search domains. To ensure physiological plausibility and mitigate overfitting, we introduce a regularization scheme that enforces positive peaks for HbO and negative peaks for HbR, thereby systematically rejecting insensible HRF shapes. We evaluated our method against seven established baseline approaches using a block‑design dataset collected from the prefrontal cortex of 37 participants performing a working memory task. The proposed approach demonstrates superior sensitivity and specificity, as it reliably detects positive HbO and negative HbR activations in expected task-evoked brain regions while preserving the typical inverse relationship between the two signals. Our adaptive HRF framework embraces hemodynamic variability and harnesses both HbO and HbR dynamics to deliver individualized, physiologically grounded activation detection, thus advancing fNIRS toward clinical translation. Our method is available as open-source software.
			- literature review
			  collapsed:: true
				- argument that HbR not suppose to have same [[cHRF]] as HbO
					- from [[Optimizing the general linear model for fNIRS - an adaptive hemodynamic response function approach]]
						- "Hoshi raised a concern about blindly adapting the GLM approach to fNIRS data and emphasized the necessity of taking hemodynamic variations into account."
			- evaluation
				- [[parametric modulator]]
			- draft
			  collapsed:: true
				- literature review
					- [[Determination of the parameters in the designed hemodynamic response function using Nelder-Mead algorithm]]
						- Over the last years, interest in understanding the neurovascular coupling (NVC) has raised rapidly. NVC can be defined as a process that links the change in regional neuronal activity to the local cerebral blood flow (CBF) [1]. Therefore, there exists a coupling between the changes in the neuronal activity and those in CBF due to functional stimulation [2]. This NVC coupling becomes the basis for currently available hemodynamics based functional neuroimaging methods including position emission tomography, intrinsic signal optical imaging, functional magnetic resonance imaging, and functional near-infrared spectroscopy (fNIRS) [3-6]. Among these aforementioned HR imaging techniques, fNIRS is relatively new and low-cost non-invasive technique, which examines the cerebral activities by emitting near-infrared light (650 nm ~ 1000 nm). fNIRS utilizes two wavelengths to determine the changesٻin oxy-hemoglobin (HbO) and deoxy-hemoglobin (HbR), concurrently [7-11]. In addition, fNIRS also provides better temporal resolution as compared to other HR techniques [6]. The recent achievement of bundled-optode theory and reduction in the delay of detecting initial dips has more improved its spatial and temporal resolution, respectively [12-14].
						- fNIRS used HR (HbO and HbR) as an indirect marker for neuronal activity. However, there exists a debate regarding spatial and temporal characteristics of the HR as an alternate of the neural activity [15]. Mainly, the HR caused by functional activation is categorized in three response components; initial dip, conventional HR, and undershoot [16-19]. The initial dip is the early decrease/increase in the HbO/HbR at the start of the activity. After the initial dip, the conventional HR duration starts in which HbO/HbR starts increasing/decreasing. The final duration of the HR is known as undershoot and after this duration the HbO/HbR comes to the baseline. To find out the shape of the HbO, a statistical comparison to a specific time series shape, known as canonical hemodynamic response function (cHRF) for the detection of neuronal activation in a particular brain area is very important [20]. The designed hemodynamic response function (dHRF) is generated by further convolving the cHRF with the experimental paradigm [21]. The dHRF is then fitted to the measured HRs to find out the active channels (i.e., a brain region) showing high correlation to the dHRF in drawing a brain functional map depicting cortical activations [22-25].
						- For the analysis of fNIRS signal, the cHRF has a key role as its shape varies among subjects, brain regions, and trials [26, 27]. The most frequently used model for cHRF is made up of two gamma functions to characterize the shape and undershoot, respectively [28, 29]. Although, NIRS-SPM and functional optical signal analysis toolboxes contains the three or more gamma basis functions to incorporate the dynamics of the initial dip in dHRF [30, 31]; but most of the fNIRS studies only used two gamma functions to model dHRF with fixed parameters. The previous studies shown that the HR can vary between subject-to-subject and trial-to-trial [32, 33]. Therefore, the dHRF designed with fixed parameters cannot incorporate the variability of HR among different brain regions, trials, and subjects. The selection of optimal parameters of cHRF for each subject to represent its appropriate time-series is very crucial. Also, another problem associated with using two gamma functions for fNIRS is that it cannot include the initial dip in the dHRF design. Therefore, assuming cHRF parameters as free unknown parameters in an optimization problem can be one possible solution to address this problem. Recently, Zafar and Hong (2018) used three gamma functions to model the dHRF with initial dip and they tried to find out the best-fit dHRF shape for each subject using optimization algorithm. They successfully demonstrated that the initial dip phase indeed occur in the dHRF design [34]. However, they have not included the physiological noises in their estimation process. The measured HR is assumed to be a linear combination of dHRF, physiological noises (mayer, cardiac, and respiration), and the baseline [20]. Therefore, further research is needed to optimize the dHRF shape by eliminating the effect of physiological noises on the HR using the optimization process.
					- [[Optimizing the general linear model for fNIRS - an adaptive hemodynamic response function approach]]
						- Functional near-infrared spectroscopy (fNIRS) offers a unique position as a neuroimaging modality for assessing human brain functions. In comparison to functional magnetic resonance imaging (fMRI), one obvious merit of fNIRS in its experimental use is the high degree of flexibility: it requires only a compact instrument installed in an ordinary environment, is less restrictive, and is tolerant of body motion. These merits enable a variety of motor, sensory, and cognitive tasks to be executed using fNIRS. 1–3 Moreover, fNIRS allows the acquisition of a wider variety of parameters than does fMRI. While fMRI measures blood oxygen level dependent (BOLD) signals mostly reflecting deoxygenated hemoglobin (deoxy-Hb) concentration changes, fNIRS can utilize both oxygenated (oxy-) and deoxy-Hb signals. In addition, fNIRS enjoys higher temporal resolution than fMRI: while the typical sampling rate of fMRI is on the order of seconds, that of fNIRS is on the order of 100 ms for typical measurements or of 10 ms for highly tuned settings.2
						- However, there remains debate over how to appropriately extract cortical activation data from Hb timeline signals, and a standardized method has yet to be established. Typically, two methods are utilized in fNIRS studies. In a classical approach, the functional data can be simply assessed by contrasting average data from the peak period against average data from the baseline period. A contrast representing task-related cortical activation may be extracted for a given subject, which is further subjected to group analyses. In a single subject, sets of baseline and task periods are statistically assessed using a paired (or one-sample) t-test. This approach has been adopted for both block and event-related designs. 4,5
						- Alternatively, a general linear model (GLM) approach, which has been established as a standard method for fMRI data analysis, has also been applied to fNIRS studies using both event 6 and block-related designs. 7 In typical GLM analyses, the functional timeline of data is regressed to a hemodynamic response function (HRF) that mimics the actual hemodynamic response, measured as a BOLD signal in fMRI experiments.8,9 The GLM describes data as a linear combination of an explanatory variable and an error term. In group analyses, the GLM is used to produce a subject-specific contrast from beta-weight in regression to the HRF, which is used for the second-level analyses. When applied to single-subject analyses, the GLM can fully utilize the temporal information for fNIRS Hb signals by increasing the degree of freedom by severalfold to achieve greater statistical power.
						- GLM analyses of the fMRI data have been developed to explain the timeline BOLD signal data observed. The crucial part of the model function of a GLM is the boxcar function, which reflects the temporal structures of the experimental paradigm and is convolved with the canonical hemodynamic response function consisting of the sequential combination of positive and negative gamma functions. 9 In addition to the HRF, its first and second derivatives (temporal and dispersion derivatives), baseline and linear trends are usually adopted as regressors in a GLM. In actual data analysis, it is the general practice to use default settings for the temporal parameters such as peak delays of the gamma functions as provided by data analysis tools such as statistical parametric mapping (SPM). 8,9
						- These parameters were first proposed by Boynton et al. to empirically describe the observed BOLD signal in response to the preceding neural activity. 8 Although these temporal parameters stand as the fundamental basis of GLM, little consideration has been given to the validity of their selection. Indeed, Boynton himself raised an alarm over the current practice of blindly using default settings for the temporal parameters as provided by analysis tools without considering possible variability of hemodynamic response between brain regions and task species. 10 In order to take such variability into consideration, some studies have modified HRF parameters to achieve a better fitting of the model function to the observed data.11,12
						- Thus, the GLM approach to fNIRS data analysis has essentially borrowed its basic framework from GLM used in typical fMRI analyses. However, several important issues need to be addressed when "localizing" fMRI-GLM to fNIRS data. Among these, the temporal coherence of timeline data has been well treated using a precoloring approach. Also, spatial inhomogeneity within multiple channel measurements has been resolved using a tube formula. Together, these solutions have been released to public domains as user-friendly toolboxes (NIRSSPM). 13 Similarly, the fNIRS GLM analysis tools of HomER 14 and fOSA 7 have also been released. On the other hand, it has been a common practice for GLM in fNIRS to adopt the temporal parameters for the hemodynamic response functions used in fMRI-GLM, which have been empirically optimized for analyzing BOLD timeline data.6,7,13,15 Since fNIRS deals with hemodynamic responses of both oxy- and deoxy-Hb signals, the temporal parameters for the fMRI BOLD signal may not suitably explain the behaviors of those Hb signals. In fact, canonical HRF being used as a predictor for both Hb signals without accounting for differences in their behaviors and variations among individual subjects has been raised as a concern regarding the GLM approach.16
						- In recent years, a few pioneering fNIRS studies have started to adjust the temporal parameters of the HRF. Minagawa-Kawai et al. explored the best-fit first peak delay values for both Hb parameters in an auditory infant study and found that the best fit was achieved at 2.8 s for oxy- and 3.4 s for deoxyHb parameters, respectively. 17 Both were shorter than the typical peak delay in fMRI of 6 s. A functional map was created based on the oxy-Hb parameter, and the relationship between the two parameters has yet to be examined. Similarly, in a simultaneous measurement using fNIRS and EEG, onset and peak delays for Gaussian functions have been adopted for oxy-Hb signal, while deoxy-Hb signal remains to be analyzed.18 Given this, there is still the need to explore model functions suitable for examining the temporal behaviors of oxy- and deoxy-Hb signals. The most practical strategy would be to adopt the tuning of the HRF temporal parameters, as has been done in fMRI analyses, for both oxy- and deoxy-Hb signals. Given the higher temporal resolution of fNIRS (subsecond order) than of fMRI (second order), we would expect that the temporal characteristics of the two hemoglobin signals could be well modeled using the GLM approach.
					- [[Data-driven HRF estimation for encoding and decoding models]]
						- These activation coefficients are computed by means of the General Linear Model (GLM) (Friston et al., 1995). While this approach has been successfully used in a wide range of studies, it does suffer from limitations (Poline and Brett, 2012). For instance, the GLM commonly relies on a data-independent canonical form of the hemodynamic response function (HRF) to estimate the activation coefficient. However it is known (Handwerker et al., 2004; Badillo et al., 2013b) that the shape of this response function can vary substantially across subjects and brain regions. This suggests that an adaptive modeling of this response function should improve the accuracy of subsequent analysis.
						- To overcome the aforementioned limitation, Finite Impulse Response (FIR) models have been proposed within the GLM framework (Dale, 1999; Glover, 1999). These models do not assume any particular shape for the HRF and amount to estimating a large number of parameters in order to identify it. While the FIR-based modeling makes it possible to estimate the activation coefficient and the HRF simultaneously, the increased flexibility has a cost. The estimator is less robust and prone to overfitting, i.e. to generalize badly to unseen data. In general, FIR models are most appropriate for studies focused on the characterization of the shape of the hemodynamic response, and not for studies that are primarily focused on detecting activation (Poldrack et al., 2011, Chapter 5)
						- Several strategies aiming at reducing the number of degrees of freedom of the FIR model - and thus at limiting the risk of overfitting - have been proposed. One possibility is to constrain the shape of the HRF to be a linear combination of a small number of basis functions. A common choice of basis is formed by three elements consisting of a reference HRF as well as its time and dispersion derivatives (Friston et al., 1998), although it is also possible to compute a basis set that spans a desired function space (Woolrich et al., 2004). More generally, one can also define a parametric model of the HRF and estimate the parameters that best fit this function (Lindquist and Wager, 2007). However, in this case the estimated HRF may no longer be a linear function of the input parameters.
						- Sensitivity to noise and overfitting can also be reduced through regularization. For example, temporal regularization has been used in the smooth FIR (Goutte et al., 2000; Ciuciu et al., 2003; Casanova et al., 2008) to favor solutions with small second order time derivative. These approaches require the setting of one or several hyperparameters, at the voxel or potentially at the parcel level (if several voxels in a pre-defined parcel are assumed to share some aspects of the HRF timecourse).
					- [[An Integrated Framework for Joint HRF and Drift Estimation and HbO/HbR Signal Improvement in fNIRS Data]]
					  collapsed:: true
						- Functional near-infrared spectroscopy (fNIRS) is a unique in vivo imaging technology that simultaneously measures the concentration changes of oxygenated (HbO) and deoxygenated (HbR) hemoglobin. It has shown great potential to analyze cognitive functions during ecologically valid paradigms as it offers a flexible environment for measuring functional brain activity [1]. It provides a balance between temporal and spatial resolution unlike in-the-field neuroimaging techniques such as functional magnetic resonance imaging (fMRI) and EEG. Furthermore, the independent observation of HbO and HbR in fNIRS measurements and access to their sum as total hemoglobin (HbT) better characterizes the governing mechanism of neuronal dynamics than the blood oxygen level-dependent (BOLD) fMRI signal alone [2]. Primary source of signal contrast in fNIRS measurements is HbO and HbR that are negatively correlated during neural activations [3] through a mechanism known as neurovascular coupling [4]. Increase in neuronal activity increases HbO and decreases HbR. The changes in tissue oxygenation associated with neural activity modulate the absorption and scattering of the infrared light through the brain tissue. In principle, HbO and HbR have different attenuation spectra with characteristic properties in the optical window of the near-infrared spectral range 680–900 nm [4], [5]. Therefore, different characterizing wavelengths are used in the optical window in fNIRS to differentiate noninvasively between the two qualitative measures associated with the neural activity. The HbO and HbR as a first approximation are modeled as a convolution of the experimental paradigm characterizing the stimulus by the hemodynamic response function (HRF), modeling the impulse response of the neurovascular system [6] that is assumed to be linear time-invariant [7].
						- HRF shape vary substantially across regions as is recently revealed by [8] in an fMRI study, apart from the understood notion of its variability across tasks and subjects. Therefore, accurate HRF estimation is essential to characterize the temporal dynamics of brain region response during activations, and the region involvement in functional and effective connectivity. Based on generalized linear model (GLM), the available methods for HRF estimation from fMRI data can be adapted to fNIRS time-series [9]. Among them, parametric HRF estimation methods offer limited flexibity by a priori choosing a nonlinear function of certain parameters that are estimated by least squares [10]. Nonparametric estimation methods allow more flexibility and offer accuracy in the estimation by inferring the HRF at each time sample [11].
					- [[Optimal hemodynamic response model for functional near-infrared spectroscopy]]
					  collapsed:: true
						- Functional near-infrared spectroscopy (fNIRS) is a non-invasive and an emerging neuro-imaging technique (Santosa et al., 2013, 2014). The brain functional information is decoded through the interpretation of the variation in the optical properties of near-infrared (NIR) light (Naseer et al., 2014). NIRS monitors regional cerebral blood flow (rCBF) variations through the absorption changes of the NIR light at wavelengths between 650–950 nm. The oxy-hemoglobin (HbO) and deoxy-hemoglobin (HbR) are two major chromospheres in the blood which absorb NIR light (Cope and Delpy, 1988). The concentration of HbO and HbR varies in the capillary blood during the rest and task sessions (Hu et al., 2013). Thus, brain functional information can be revealed by the estimation of HbO and HbR. fNIRS, with the ability to estimate both chromospheres, is a potential brain imaging modality (Kamran and Hong, 2014). Functional-magnetic resonance imaging (fMRI) (Cohen et al., 2014; Zhou et al., 2014) and electro-encephalography (EEG) are most frequently used cortical imaging modalities in past. In comparison, the huge size of fMRI and its paramagnetic constraints and low spatial resolution of EEG (Soekadar et al., 2014) enhance the potential position of fNIRS with good temporal resolution applicable to braincomputer interface (BCI) applications (Hu et al., 2010). Its spatial resolution is affected by the low penetration depth but lies in between fMRI and EEG (Boudriay et al., 2014). In addition to these attributes, its portability, safety and low cost features makes it on top position for rehabilitation and BCI applications (Khan et al., 2014).
				- brainstorm
					- although our method capture variability in HRF shape, but polarity must be constraint via the tolerance
				- methodology
					- dataset
					  collapsed:: true
						- [[Optimizing Mental Workload Estimation by Detecting Baseline State Using Vector Phase Analysis Approach]]
							- The proposed method was applied on the lab-based fNIRS dataset published in [21]. Briefly, 10-Hz sampling rate fNIRS data were collected from a total of 38 right-handed healthy university students performing mental arithmetic task using a closed-loop brain training system, specifically to optimize the mental workload at WM-related brain region. A 3 × 11 probe layout with a standard source-detector distance of 30 mm was used for the fNIRS recording over the PFC (see Fig. 3). The experimental paradigm began with a 25-s pre-task and followed by a total of 60 block repetitions consists of 15-s task and 15-s rest periods. The whole protocol lasted approximately 30 min. During the task period, subjects were asked to mentally calculate and solve as many four-choice mathematical questions as possible. Addition or subtraction or a mixture of both were used for the mathematical questions, comprising of six difficulty levels from the easiest two single digits to the hardiest three double digits.
						- [[Functional Near-Infrared Spectroscopy Adaptive Cognitive Training System (FACTS) for Cognitive Underload and Overload Prevention: A Feasibility Study]]
							- The participants were recruited through purposive sampling with specific inclusion criteria: 1) Right-handed; 2) No history of psychiatric or neurological disorder; 3) Have normal or corrected-to-normal vision; 4) Able to communicate in English. A total of 38 healthy right-handed local university students matched for age and gender participated in the feasibility study.
							- The medical research ethics committee of Universiti Kuala Lumpur Royal College of Medicine Perak has consented to the study protocol used in the study (reference number: UniKLR-CMP/MREC/2018/019) and the study was performed in compliance with the Declaration of Helsinki. Informed consent along with demographic information were obtained and the participants were remunerated for their participation.
							- In the end, the data collected from one participant, who did not complete his second session due to a technical glitch, was excluded. The final group of participants was reduced to 19 males and 18 females, with a mean ± standard deviation age of 23.41 ± 3.32 years. All but one underwent the second session at least a week apart from the first (mean ± standard deviation duration between sessions, 8.00 ± 2.60 days). The participants reported similar sleep duration the night before their first and second session, with a mean ± standard deviation sleep of 6.65 ± 0.22 and 6.96 ± 0.21 hours respectively.
							- Mental arithmetic was used as the cognitive training task. After resting for 15 s, participants were asked to solve as many on-screen four-choice mathematical problems mentally as possible, at their own pace and within their capability, during the following 15-s task period. A 4-button Serial Response Box (Psychology Software Tools, Inc.) was also utilized to collect the participants' responses. Fig. 1b shows the paradigm for a single task trial. The mathematical problems only involved addition or subtraction or a mix of both. There were six levels of difficulty, each with a distinctive set of operands: 1) Two single digits; 2) Three single digits; 3) Two double digits; 4) Two single and one double digits; 5) One single and two double digits; and 6) Three double digits. The single-digit operands ranged from 1 to 9 while the three-digit operands lied between 10 and 99. All the operands and answers were non-negative. Besides that, there were no repeating number in all the mathematical problems.
							- First, a 10-minute pre-task assessment was carried out not only to determine the participants' optimal level of difficulty but also to sample their baseline performance. The participants sat through mental arithmetic task of all six difficulty levels (three trials per level) in a randomized sequence. In accordance to Yerkes–Dodson Law in the context of hemodynamics, peak brain activation is achieved when the task level at hand is appropriate [37]. An activation consists of an increase in oxygenated hemoglobin (oxy-Hb) and an almost antiphase decrease in deoxygenated hemoglobin (deoxy-Hb) [40]. In the task, each trial yielded an activation value and the final 18 activation values were averaged down to only one average value per level. For each participant, the level eliciting the largest average value was eventually picked as the participant's optimal level.
							- In environmental settings similar to those in the pre-task assessment, participants underwent two extended sessions of the mental arithmetic task under nonadaptive and adaptive conditions in a counterbalanced design within at least two weeks. To intentionally induce mental overload, both sessions contained 60 trials and lasted approximately 30 minutes.
							- Throughout nonadaptive condition, the task difficulty was fixed at the participant-specific optimal level predetermined from the pre-task assessment.
					- Preprocessing
					  collapsed:: true
						- [[Optimizing Mental Workload Estimation by Detecting Baseline State Using Vector Phase Analysis Approach]]
							- MATLAB (Mathworks Inc., New York, USA) was primarily used for the data analysis.  The light intensity data were transformed to the optical density data.
							- For every channel, the optical density data under the wavelengths of 695 and 830 nm were converted to the time-series HbO and HbR signals using the modified Beer-Lambert law [27]. These signals were obtained in the unit of millimolar millimeter (mM·mm), a product of the hemoglobin concentration change and optical path length.
							- A third order Butterworth bandpass filter with cutoff frequencies of 0.01 to 0.09 Hz was then applied to remove the slow drifts (<0.01 Hz), Mayer wave (∼0.1 Hz), respiration (∼0.3 Hz), heartbeat (∼1 Hz), and high frequency noise (3–5 Hz) [28].
						- [[An fNIRS investigation of novel expressed emotion stimulations in schizophrenia]]
							- MATLAB (MathWorks Inc., United States) was primarily used for data analysis. Prior to analysis, about 5% of the total number of channels was eliminated due to the poor signal-to-noise ratio (SNR; power ratio of 0.005–0.2 Hz to 4–5 Hz less than 20 dB). The light intensity data were transformed into the optical density data and were followed by motion artifacts correction with a temporal derivative distribution repair algorithm on a channel-by-channel basis75 . Modified Beer–Lambert law was applied to obtain time-series HbO and HbR signals in the unit of a millimolar millimeter (mM·mm)76 . Third-order Butterworth bandpass filter with cutoff frequencies between 0.005 and 0.2 Hz was used to remove baseline drift and high-frequency noise.
					- evaluation
						- BA
							- To identify the Brodmann area (BA), the probe layout was mapped onto the head model applied in [25] as the reference position was similar.
								- [[Optimizing Mental Workload Estimation by Detecting Baseline State Using Vector Phase Analysis Approach]]
				- result and discussion
					- tolerance tunning
						- figure shows the
					- line fitting
					-
		- Second paper: multi-channel VPA
			- Targets
				- (i) IEEE Journal of Biomedical and Health Informatics, impact factor 6.7, Q1
				- (ii) IEEE Transactions on Cognitive and Developmental Systems, impact factor 5, Q1
				- (iii) IEEE Transactions on Neural Systems and Rehabilitation Engineering, impact factor 4.8, Q1
			- Result
				- nsga result
					- nsga_20260112.mat
					  collapsed:: true
						- pso_file = 'C:\Users\koksy\OneDrive\Desktop\PHD\Dr Lim Lam Ghai\Matlab\Project2\hrf_obj\hrf_param_20260110.mat';
						- lb = zeros(1,2+total_channel_num);
						  ub = ones(1,2+total_channel_num);
						  A = [1 -1 zeros(1,total_channel_num)];
						  b = 0;
						  options = optimoptions('gamultiobj','Display','iter','PopulationSize',250,'MaxStallGenerations', 250,'UseParallel',true,'UseVectorized',false);
						- optFun = @(x)vpa_obj_func(x,ds_HbO,ds_HbR,ds_timestamp,valid_subject(human_id,:), ...
						          squeeze(hbo_betas(human_id,:,:)),squeeze(hbo_sigmas(human_id,:,:)), ...
						          ,total_channel_num,total_trial_num);
					- nsga_20260115.mat
					  collapsed:: true
						- pso_file = 'C:\Users\koksy\OneDrive\Desktop\PHD\Dr Lim Lam Ghai\Matlab\Project2\hrf_obj\hrf_param_20260110.mat';
						- lb = zeros(1,2+total_channel_num);
						  ub = ones(1,2+total_channel_num);
						  A = [1 -1 zeros(1,total_channel_num)];
						  b = 0;
						  options = optimoptions('gamultiobj','Display','iter','PopulationSize',250,'MaxStallGenerations', 250,'UseParallel',true,'UseVectorized',false);
						- optFun = @(x)vpa_obj_func2(x,ds_HbO,ds_HbR,ds_timestamp,valid_subject(human_id,:), ...
						          squeeze(hbo_betas(human_id,:,:)),squeeze(hbo_sigmas(human_id,:,:)), ...
						          squeeze(hbr_betas(human_id,:,:)),squeeze(hbr_sigmas(human_id,:,:)) ...
						          ,total_channel_num,total_trial_num);
					- nsga_20260116.mat
					  id:: 69691982-64a4-4044-b8a3-31000b024075
					  collapsed:: true
						- pso_file = 'C:\Users\koksy\OneDrive\Desktop\PHD\Dr Lim Lam Ghai\Matlab\Project2\hrf_obj\hrf_param_20260110.mat';
						- lb = zeros(1,2+total_channel_num);
						  ub = ones(1,2+total_channel_num);
						  A = [1 -1 zeros(1,total_channel_num)];
						  b = 0;
						  options = optimoptions('gamultiobj','Display','iter','PopulationSize',250,'MaxStallGenerations', 250,'UseParallel',true,'UseVectorized',false);
						- excel_BA_path = "C:\Users\koksy\OneDrive\Desktop\PHD\Dr Lim Lam Ghai\channel BA.xlsx";
						  excel_BA = readmatrix(excel_BA_path,"Sheet",'DLPFC','Range','U2:U53');
						  excel_BA(isnan(excel_BA)) = 0;
						  BA_weight = excel_BA / sum(excel_BA); 
						  BA_weight = reshape(BA_weight,1,numel(BA_weight),1);
						  hbo_betas = hbo_betas .* BA_weight;
						  hbo_sigmas = hbo_sigmas .* BA_weight;
						  hbr_betas = hbr_betas .* BA_weight;
						  hbr_sigmas = hbr_sigmas .* BA_weight;
						- optFun = @(x)vpa_obj_func2(x,ds_HbO,ds_HbR,ds_timestamp,valid_subject(human_id,:), ...
						          squeeze(hbo_betas(human_id,:,:)),squeeze(hbo_sigmas(human_id,:,:)), ...
						          squeeze(hbr_betas(human_id,:,:)),squeeze(hbr_sigmas(human_id,:,:)) ...
						          ,total_channel_num,total_trial_num);
					- nsga_20260117.mat
					  collapsed:: true
						- pso_file = 'C:\Users\koksy\OneDrive\Desktop\PHD\Dr Lim Lam Ghai\Matlab\Project2\hrf_obj\hrf_param_20260110.mat';
						- lb = zeros(1,2+total_channel_num);
						  ub = ones(1,2+total_channel_num);
						  A = [1 -1 zeros(1,total_channel_num)];
						  b = 0;
						  options = optimoptions('gamultiobj','Display','iter','PopulationSize',250,'MaxStallGenerations', 250,'UseParallel',true,'UseVectorized',false);
						- excel_BA_path = "C:\Users\koksy\OneDrive\Desktop\PHD\Dr Lim Lam Ghai\channel BA.xlsx";
						  excel_BA = readmatrix(excel_BA_path,"Sheet",'DLPFC','Range','U2:U53');
						  excel_BA(isnan(excel_BA)) = 0;
						  BA_weight = excel_BA / sum(excel_BA); 
						  BA_weight = reshape(BA_weight,1,numel(BA_weight),1);
						  hbo_betas = hbo_betas .* BA_weight;
						  hbo_sigmas = hbo_sigmas .* BA_weight;
						  hbr_betas = hbr_betas .* BA_weight;
						  hbr_sigmas = hbr_sigmas .* BA_weight;
						- optFun = @(x)vpa_obj_func(x,ds_HbO,ds_HbR,ds_timestamp,valid_subject(human_id,:), ...
						          squeeze(hbo_betas(human_id,:,:)),squeeze(hbo_sigmas(human_id,:,:)), ...
						          total_channel_num,total_trial_num);
					- nsga_20260118.mat
						- pso_file = 'C:\Users\koksy\OneDrive\Desktop\PHD\Dr Lim Lam Ghai\Matlab\Project2\hrf_obj\hrf_param_20260110.mat';
						- lb = zeros(1,2+total_channel_num);
						  ub = ones(1,2+total_channel_num);
						  A = [1 -1 zeros(1,total_channel_num)];
						  b = 0;
						  options = optimoptions('gamultiobj','Display','iter','PopulationSize',250,'MaxStallGenerations', 250,'UseParallel',true,'UseVectorized',false);
						- excel_BA_path = "C:\Users\koksy\OneDrive\Desktop\PHD\Dr Lim Lam Ghai\channel BA.xlsx";
						  excel_BA = readmatrix(excel_BA_path,"Sheet",'DLPFC','Range','U2:U53');
						  excel_BA(isnan(excel_BA)) = 0;
						  BA_weight = excel_BA / sum(excel_BA); 
						  BA_weight = reshape(BA_weight,1,numel(BA_weight),1);
						  hbo_betas = hbo_betas .* BA_weight;
						  hbo_sigmas = hbo_sigmas .* BA_weight;
						  hbr_betas = hbr_betas .* BA_weight;
						  hbr_sigmas = hbr_sigmas .* BA_weight;
						- hbo_betas(hbo_betas >= 0) = 0;
						  hbr_betas(hbr_betas <= 0) = 0;
						- optFun = @(x)vpa_obj_func(x,ds_HbO,ds_HbR,ds_timestamp,valid_subject(human_id,:), ...
						          squeeze(hbo_betas(human_id,:,:)),squeeze(hbo_sigmas(human_id,:,:)), ...
						          total_channel_num,total_trial_num);
				- objective function hrf
					- hrf_param_20260110.mat
						- tolerance = 0.05;
						  
						  P_lb_hbo = [0 4 2 2 0 0];
						  P_ub_hbo = [3 8 10 8 0.1 0.5];
						  
						  P_lb_hbr = [0 4 2 2 0 0];
						  P_ub_hbr = [4.5 14 10 12 0.25 0.5];
						  
						  hbo_param = zeros(total_subject_num,total_channel_num,total_trial_num,length(P_lb_hbo));
						  hbr_param = zeros(total_subject_num,total_channel_num,total_trial_num,length(P_lb_hbr));
				- original hrf
					- hrf_param_20260108.mat
					  collapsed:: true
						- tolerance = 0.15;
						  
						  P_lb_hbo = [0 4 2 2 0 0];
						  P_ub_hbo = [3 8 10 8 0.1 0.5];
						  
						  P_lb_hbr = [0 4 2 2 0 0];
						  P_ub_hbr = [4.5 14 10 12 0.25 0.5];
					- hrf_param_20260109.mat
					  collapsed:: true
						- tolerance = 0.10;
						  
						  P_lb_hbo = [0 4 2 2 0 0];
						  P_ub_hbo = [3 8 10 8 0.1 0.5];
						  
						  P_lb_hbr = [0 4 2 2 0 0];
						  P_ub_hbr = [4.5 14 10 12 0.25 0.5];
				- vpa hrf
					- hrf_param_20260112.mat
					  collapsed:: true
						- ideal_fval = [0 1 0];
						  weight_fval = [1 1 1];
						  
						  load 'C:\Users\koksy\OneDrive\Desktop\PHD\Dr Lim Lam Ghai\Matlab\Project2\nsga_result\nsga_20260112.mat';
						- snr_thres = 20;
						  tolerance = 0.10;
						  
						  P_lb_hbo = [0 4 2 2 0 0];
						  P_ub_hbo = [3 8 10 8 0.1 0.5];
						  
						  P_lb_hbr = [0 4 2 2 0 0];
						  P_ub_hbr = [4.5 14 10 12 0.25 0.5];
			- result and discussion
				- [[parametric modulator]]
				- [[multi-voxel pattern analysis]]
				- optimization of parameters
				- inter-subject result analysis
					- Number of OBB
					- Bar chart of Beta (Group average)
					- Bar chart of t-value (one sample t-test)
					- Excel file of p-value (paired t-test)
					- Group Block Plot
				- intra-subject result analysis
					- Fixed ROI Channel: choose few subjects to compare (subjects which has lots of OBB vs less OBB)
				- comparison of performance with other methods
					- should I do comparison with single channel VPA on the previously defined ROI
				- correlation with response time
		- Third paper: Deep learning
		- Forth paper: Real time baseline return detection
			- task:
				- n-back
				- stroop task
				- verbal fluency
				- finger tapping