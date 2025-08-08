document.addEventListener('DOMContentLoaded', function() {
    const sportsCards = document.querySelectorAll('.sports-card');
    const gamePopup = document.getElementById('gamePopup');
    const selectedGameElement = document.getElementById('selectedGame');
    const battleMessageElement = document.getElementById('battleMessage');

    sportsCards.forEach(card => {
        card.addEventListener('click', function() {
            const sportName = this.getAttribute('data-sport');
            
            // Add click animation
            this.classList.add('clicked');
            
            // Remove animation class after animation completes
            setTimeout(() => {
                this.classList.remove('clicked');
            }, 600);
            
            // Show popup after a short delay
            setTimeout(() => {
                showGameSelection(sportName);
            }, 300);
        });

        // Add hover sound effect simulation (visual feedback)
        card.addEventListener('mouseenter', function() {
            this.style.transform = 'scale(1.03) translateY(-5px)';
        });

        card.addEventListener('mouseleave', function() {
            if (!this.classList.contains('clicked')) {
                this.style.transform = 'scale(1) translateY(0)';
            }
        });
    });

    function showGameSelection(sportName) {
        selectedGameElement.textContent = `You Selected ${sportName}!`;
        battleMessageElement.textContent = `Get Ready for an Epic ${sportName} Battle!`;
        
        gamePopup.classList.add('active');
        
        // Add body scroll lock
        document.body.style.overflow = 'hidden';
    }

    // Close popup function (global scope for onclick)
    window.closePopup = function() {
        gamePopup.classList.remove('active');
        document.body.style.overflow = 'auto';
        
        // Reset all card transforms
        sportsCards.forEach(card => {
            card.style.transform = 'scale(1) translateY(0)';
        });
    };

    // Close popup when clicking outside
    gamePopup.addEventListener('click', function(e) {
        if (e.target === gamePopup) {
            closePopup();
        }
    });

    // Close popup with Escape key
    document.addEventListener('keydown', function(e) {
        if (e.key === 'Escape' && gamePopup.classList.contains('active')) {
            closePopup();
        }
    });

    // Add smooth scrolling and page load animation
    window.addEventListener('load', function() {
        document.body.style.opacity = '0';
        document.body.style.transition = 'opacity 0.5s ease-in-out';
        
        setTimeout(() => {
            document.body.style.opacity = '1';
        }, 100);

        // Animate cards on load
        sportsCards.forEach((card, index) => {
            card.style.opacity = '0';
            card.style.transform = 'translateY(50px)';
            card.style.transition = 'all 0.6s ease-in-out';
            
            setTimeout(() => {
                card.style.opacity = '1';
                card.style.transform = 'translateY(0)';
            }, 200 + (index * 100));
        });
    });

    // Add parallax effect to background
    window.addEventListener('scroll', function() {
        const scrolled = window.pageYOffset;
        const parallax = document.querySelector('.container');
        const speed = scrolled * 0.5;
        
        if (parallax) {
            parallax.style.transform = `translateY(${speed}px)`;
        }
    });

    // Add touch support for mobile devices
    sportsCards.forEach(card => {
        card.addEventListener('touchstart', function() {
            this.style.transform = 'scale(1.03) translateY(-5px)';
        });

        card.addEventListener('touchend', function() {
            setTimeout(() => {
                if (!this.classList.contains('clicked')) {
                    this.style.transform = 'scale(1) translateY(0)';
                }
            }, 150);
        });
    });
});

// Performance optimization: Debounce resize events
let resizeTimeout;
window.addEventListener('resize', function() {
    clearTimeout(resizeTimeout);
    resizeTimeout = setTimeout(function() {
        // Recalculate any size-dependent elements if needed
        const cards = document.querySelectorAll('.sports-card');
        cards.forEach(card => {
            card.style.transition = 'none';
            setTimeout(() => {
                card.style.transition = 'all 0.4s ease-in-out';
            }, 50);
        });
    }, 250);
});
