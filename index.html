<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mission du Jour - La Révélatrice</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600&display=swap');
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
            background: linear-gradient(135deg, #fef7f0 0%, #fff2e8 100%);
            padding: 0;
            margin: 0;
            min-height: 200px;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        
        .widget-container {
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            border-radius: 16px;
            padding: 24px;
            box-shadow: 0 8px 32px rgba(247, 147, 26, 0.1);
            border: 1px solid rgba(247, 147, 26, 0.1);
            max-width: 450px;
            width: 100%;
            margin: 16px;
            position: relative;
            overflow: hidden;
        }
        
        .widget-container::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 4px;
            background: linear-gradient(90deg, #f7931a 0%, #ff8c69 100%);
        }
        
        .header {
            display: flex;
            align-items: center;
            justify-content: space-between;
            margin-bottom: 16px;
        }
        
        .logo {
            display: flex;
            align-items: center;
            gap: 8px;
        }
        
        .brand {
            font-size: 14px;
            font-weight: 600;
            color: #f7931a;
            letter-spacing: 0.5px;
        }
        
        .emoji {
            font-size: 18px;
        }
        
        .date {
            font-size: 12px;
            color: #8b8b8b;
            font-weight: 400;
        }
        
        .mission-content {
            text-align: center;
        }
        
        .mission-title {
            font-size: 16px;
            font-weight: 600;
            color: #2d2d2d;
            margin-bottom: 12px;
            letter-spacing: -0.2px;
        }
        
        .mission-text {
            font-size: 15px;
            line-height: 1.5;
            color: #4a4a4a;
            font-weight: 400;
            font-style: italic;
            margin-bottom: 16px;
        }
        
        .dimension-tag {
            display: inline-block;
            background: linear-gradient(135deg, #f7931a15, #ff8c6915);
            color: #f7931a;
            padding: 6px 12px;
            border-radius: 20px;
            font-size: 11px;
            font-weight: 500;
            text-transform: uppercase;
            letter-spacing: 0.5px;
            border: 1px solid rgba(247, 147, 26, 0.2);
        }
        
        .refresh-hint {
            margin-top: 12px;
            font-size: 10px;
            color: #999;
            text-align: center;
        }
        
        @media (max-width: 480px) {
            .widget-container {
                margin: 8px;
                padding: 20px;
            }
            
            .mission-text {
                font-size: 14px;
            }
        }
    </style>
</head>
<body>
    <div class="widget-container">
        <div class="header">
            <div class="logo">
                <span class="emoji">✨</span>
                <span class="brand">LA RÉVÉLATRICE</span>
            </div>
            <div class="date" id="currentDate"></div>
        </div>
        
        <div class="mission-content">
            <h3 class="mission-title">Mission du Jour</h3>
            <p class="mission-text" id="missionText"></p>
            <span class="dimension-tag" id="dimensionTag"></span>
        </div>
        
        <div class="refresh-hint">
            Se renouvelle chaque jour 🌸
        </div>
    </div>

    <script>
        // Missions organisées par dimension et temporalité
        const missions = {
            passé: {
                corps: [
                    "Identifie une habitude héritée de ton enfance qui ne te sert plus et libère-toi en conscience.",
                    "Reconnecte avec ton corps d'enfant : quel mouvement t'apportait de la joie pure ?",
                    "Honore une cicatrice physique en reconnaissant la force qu'elle représente.",
                    "Écris une lettre de gratitude à ton corps pour tout ce qu'il a traversé.",
                    "Retrouve un aliment de ton enfance et savoure-le en pleine conscience."
                ],
                âme: [
                    "Identifie une blessure émotionnelle devenue ta plus grande force aujourd'hui.",
                    "Pardonne à ton moi du passé pour une décision que tu regrettes encore.",
                    "Reconnais un pattern familial que tu as consciemment choisi de transformer.",
                    "Célèbre une version passée de toi qui a fait preuve d'un courage immense.",
                    "Écris trois qualités que tu as développées grâce à tes épreuves."
                ],
                pensée: [
                    "Questionne une croyance limitante héritée de ton éducation.",
                    "Identifie un mensonge que tu te racontais sur toi-même et réécris ta vérité.",
                    "Reconnais une leçon précieuse apprise dans une période difficile.",
                    "Transforme un 'je ne peux pas' du passé en 'j'apprends à'.",
                    "Célèbre une décision courageuse qui a changé ta trajectoire."
                ],
                esprit: [
                    "Honore tes ancêtres en reconnaissant un don qu'ils t'ont transmis.",
                    "Connecte-toi à la sagesse d'une version plus jeune de toi.",
                    "Médite sur le chemin parcouru depuis tes plus grands défis.",
                    "Reconnais comment tes épreuves t'ont rapprochée de ta mission de vie.",
                    "Célèbre ta résilience spirituelle face aux tempêtes du passé."
                ]
            },
            présent: {
                corps: [
                    "Offre à ton corps un moment de pure gratitude et d'attention bienveillante.",
                    "Écoute un besoin physique que tu ignores depuis trop longtemps.",
                    "Bouge ton corps d'une façon qui honore ta féminité et ta force.",
                    "Crée un rituel beauté qui célèbre qui tu es maintenant.",
                    "Nourris ton corps avec intention et présence totale."
                ],
                âme: [
                    "Identifie l'émotion que tu évites et accueille-la avec compassion.",
                    "Exprime une vérité que tu gardes pour toi depuis trop longtemps.",
                    "Pose un acte d'amour-propre radical aujourd'hui.",
                    "Reconnecte avec une part de toi que tu as mise de côté.",
                    "Célèbre ta sensibilité comme une force, pas une faiblesse."
                ],
                pensée: [
                    "Choisis consciemment une pensée qui t'élève plutôt qu'une qui t'limite.",
                    "Questionne une évidence dans ta vie et explore d'autres possibilités.",
                    "Transforme un problème en opportunité de croissance.",
                    "Écris trois vérités sur qui tu es vraiment maintenant.",
                    "Remplace un 'je dois' par un 'je choisis' dans ta journée."
                ],
                esprit: [
                    "Connecte-toi à ton intuition pour une décision importante.",
                    "Médite sur ta mission de vie et pose un acte aligné.",
                    "Honore le sacré dans un moment ordinaire de ta journée.",
                    "Écoute le message que l'univers te transmet maintenant.",
                    "Pose un geste qui reflète tes valeurs les plus profondes."
                ]
            },
            futur: {
                corps: [
                    "Visualise ton corps dans 5 ans et pose un acte bienveillant pour cette femme.",
                    "Plante une graine de santé qui fleurira dans ton futur.",
                    "Investis dans une habitude corporelle qui servira tes rêves.",
                    "Prépare ton corps à porter tes ambitions avec grâce.",
                    "Imagine l'énergie dont tu auras besoin demain et cultive-la aujourd'hui."
                ],
                âme: [
                    "Écris à la femme que tu seras dans 10 ans pour la rassurer.",
                    "Pose un acte de foi envers tes rêves les plus audacieux.",
                    "Cultive une qualité émotionnelle nécessaire à ta vision.",
                    "Libère une peur qui freine ton expansion future.",
                    "Nourris l'espoir en créant une première étape vers ton idéal."
                ],
                pensée: [
                    "Visualise ta réussite et identifie la première action à poser.",
                    "Développe une compétence qui servira ta vision à long terme.",
                    "Questionne : 'Comment la femme que je veux devenir agirait-elle ?'",
                    "Planifie une action audacieuse pour tes 90 prochains jours.",
                    "Transforme un rêve vague en objectif concret et mesurable."
                ],
                esprit: [
                    "Médite sur l'héritage que tu veux laisser au monde.",
                    "Connecte-toi à ta vision spirituelle et pose un acte prophétique.",
                    "Prie ou manifeste pour la femme que tu es en train de devenir.",
                    "Honore tes ancêtres futurs en étant celle qu'ils seront fiers de connaître.",
                    "Aligne une décision présente sur ta mission d'âme ultime."
                ]
            }
        };

        // Fonction pour obtenir la date actuelle
        function getCurrentDate() {
            const options = { 
                weekday: 'long', 
                year: 'numeric', 
                month: 'long', 
                day: 'numeric'
            };
            return new Date().toLocaleDateString('fr-FR', options);
        }

        // Fonction pour générer un index basé sur la date
        function getDayIndex() {
            const today = new Date();
            const start = new Date(today.getFullYear(), 0, 0);
            const diff = today - start;
            return Math.floor(diff / (1000 * 60 * 60 * 24));
        }

        // Fonction pour sélectionner la mission du jour
        function getDailyMission() {
            const dayIndex = getDayIndex();
            
            // Cycle sur 30 jours pour la temporalité
            const temps = ['passé', 'présent', 'futur'];
            const tempsIndex = Math.floor(dayIndex / 10) % 3;
            const selectedTemps = temps[tempsIndex];
            
            // Cycle sur les dimensions
            const dimensions = ['corps', 'âme', 'pensée', 'esprit'];
            const dimensionIndex = dayIndex % 4;
            const selectedDimension = dimensions[dimensionIndex];
            
            // Sélection de la mission spécifique
            const missionsArray = missions[selectedTemps][selectedDimension];
            const missionIndex = Math.floor(dayIndex / 4) % missionsArray.length;
            const selectedMission = missionsArray[missionIndex];
            
            return {
                mission: selectedMission,
                dimension: selectedDimension.toUpperCase(),
                temps: selectedTemps
            };
        }

        // Initialisation
        function initWidget() {
            document.getElementById('currentDate').textContent = getCurrentDate();
            const dailyMission = getDailyMission();
            document.getElementById('missionText').textContent = dailyMission.mission;
            document.getElementById('dimensionTag').textContent = dailyMission.dimension;
        }

        // Lancement au chargement
        window.addEventListener('load', initWidget);
    </script>
</body>
</html>
