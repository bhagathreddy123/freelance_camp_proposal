# README

This README would normally document whatever steps are necessary to get the
application up and running.

rails new freelance_camp_proposal --api -T -d postgresql

Proposal.create!(customer: "Google",portfolio_url: 'http://portfolio.jordanhudgens.com',
	tools: 'Ruby on Rails, Angular 2, and Postgres',
	estimated_hours: 120,
	hourly_rate: 120,
	weeks_to_complete: 12,
	client_email: 'katta04.bhagath@gmail.com')